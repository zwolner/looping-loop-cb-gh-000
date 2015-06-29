# The Loop Construct

The first looping construct that we'll discuss is `loop`. This is the simplest looping construct that we have in Ruby. It simply executes a block (the code that is between the `do` and `end` keywords). Try this in IRB in your Terminal:

```ruby
loop do
  puts "I have found the Time Machine!"
end
```

This will output `I have found the Time Machine!` an infinite number of times in your Terminal. Use Control + C to break out of the loop in your terminal.

%%%

## Using the `loop` method

It's your first year at Hogwarts and you're having a tough time getting the hang of that levitation spell. Fill out the content of the method `looping` puts the 
levitation charm "Wingardium Leviosa" 10 times using the `loop` keyword. 

```ruby
def looping
	#your code here
end

~~~solution

def looping 
	loop do 
		puts "Wingardium Leviosa"
		puts "Wingardium Leviosa"
		puts "Wingardium Leviosa"
		puts "Wingardium Leviosa"
		puts "Wingardium Leviosa"
		puts "Wingardium Leviosa"
		puts "Wingardium Leviosa"
	end
end

looping

~~~validation
looping_string = "Wingardium Leviosa\nWingardium Leviosa\nWingardium Leviosa\nWingardium Leviosa\nWingardium Leviosa\nWingardium Leviosa\nWingardium Leviosa\n"

expect{ looping }.to output(looping_string).to_stdout

```

%%%
