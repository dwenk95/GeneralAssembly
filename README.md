GeneralAssembly
===============
(1..100).each do |i|
  #In my first line of code the each method prints out the numbers between 1-100.
  if (i % 3 == 0) & (i % 5 == 0) 
      puts "FizzBuzz!"
      #In this line I create the if conditional statement that states if the integer is divisible by 3 and by 5 then it puts Fizzbuzz!
    elsif i % 3 == 0
      puts "Fizz"
    #In this line I create the elsif statement that says if the integer is divisible by 3 then it writes fizz.
    elsif i % 5 == 0
      puts "Buzz"
    #In this line I create elsif statement that says if the integer is divisible by 5 then it writes buzz.
    else
      puts i
      # In this else statement it says if none of the above statements apply then it just puts the integer.
    end # This ends the if/else statements.
  end #This ends the .each do statement.
