# RUBY :gem:

## Author

<img src="https://miro.medium.com/max/1680/0*X1fKPlobtEieQKJP." width="400">

**Yukihoro Matsumoto a.k.a _Matz_**


matz@ruby-lang.org

## History Of The Language

### ***What is Ruby ?***
Ruby is a **simple and powerful** _object-oriented_ programming language.Like Perl, Ruby is good at text processing. Like Smalltalk, everything in Ruby is an object, and Ruby has blocks, iterators, meta-classes and other good stuff.
You can use Ruby to write servers, experiment with prototypes, and for everyday programming tasks. As a fully-integrated object-oriented language, Ruby scales well.



### ***The Name “Ruby”***

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcR8AT55mDo5i0ZtIPqLzRsU79t6uPjZzS5gCR3M2XtyL3QQDikV&usqp=CAU" width="300">

The **name "Ruby"** originated during an online chat session between ***Matsumoto*** and ***Keiju Ishitsuka*** on _February 24, 1993_, before any code had been written for the language.

Initially two names were proposed: ***"Coral" and "Ruby"***.

Matsumoto chose the latter in a later e-mail to Ishitsuka.Matsumoto later noted a factor in choosing the name _"Ruby"_ – it was the birthstone of one of his colleagues

Later, he realized that Ruby comes right after Perl in several situations. In birthstones, pearl is June, ruby is July. When measuring font sizes, pearl is *5pt*, ruby is *5.5pt*. He thought Ruby was a good name for a programming language newer ***(and hopefully better)*** than _Perl_.

### Which Language influenced it 

_Ruby is a language of careful balance_. Its creator, Yukihiro “_Matz_” Matsumoto, blended parts of his favorite languages (**_Perl, Smalltalk, Eiffel, Ada, and Lisp_**) to form a new language that _balanced functional programming_ with **imperative programming**.
He has often said that he is 

> _Trying to make Ruby **natural**, **not simple**_

in a way that mirrors life.Building on this,he adds:

> Ruby is **_simple in appearance_**, but is **_very complex inside_**, just _like our human body_.


### Who/When Invented It

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcSF3Q_OwhaPyHnTvwgz_7nX2W34Tijv1bRDZD8A8do9pQuNrt5J&usqp=CAU" width="300">

**Yukihiro Matsumoto** ( a.k.a. Matz, born 14 April 1965) is a Japanese _computer scientist_ and _software programmer_ best known as the chief designer of the *Ruby programming language* and its reference implementation, _Matz's Ruby Interpreter_ (**MRI**). His demeanor has brought about a motto in the Ruby community: 
> Matz is nice and so we are nice" 

commonly abbreviated as MINASWAN.

### First publication

The *first public release of Ruby* *0.95* was announced on Japanese domestic newsgroups on **December 21, 1995**. Subsequently, three more versions of Ruby were released in two days. The release coincided with the launch of the Japanese-language ruby-list mailing list, which was the first mailing list for the new language.

### ***Features of Ruby***

- Simple syntax,

- Normal Object-oriented Features (e.g. class, method calls)

- Advanced Object-oriented Features (e.g. mix-in, singleton-method)

- Operator overloading,

- Exception handling,

- Iterators and closures,

- Garbage collection,

- Dynamic loading (depending on the architecture),

- Highly Portable (works on many Unix-like/POSIX compatible platforms as well as Windows, macOS, Haiku, etc.)

## Why It Was Invented 
According to Ruby's creator, 

Matz, this programming language was created to **act as** a sensible buffer between human programmers and the underlying computing machinery_. Unlike some other programming languages, notably _C and C++_ etc., where the onus is on the programmer to do all the heavy lifting and make sure all little details are correctly specified, **_Ruby was designed to take a lot of that brunt off the programmer's shoulders._**

- Matz said that he wanted Ruby to act like a _'smart servant'_. What he meant by that is that a smart servant, such as _Ruby_, **would be attentive to human needs and sensitive to human frailty**. So if a programmer needs to implement a working program that would correctly instruct the CPU on how to process the data, such needs are traditionally hard to meet due to copious amount of intricate details a programmer must attend to. Spending so much time on excruciating minutia needed to satisfy finicky CPU leaves very little time for the programmer to focus on higher level logic, such as business rules and the intended workflow. Simply put, being heads-down deep in the weeds of computing bits and bytes creates a situation where _it is difficult to see forest for the trees_.

- Ruby proposes to **take away a lot of such annoying details** and to therefore free the programmer to rise above the sludge of bits and bytes and to dedicate their precious time to solving business problems, *not computing problems*.

- Ruby **is not the only '_smart servant_' language**, of course. Other similarly intended languages existed before Ruby was created. One such notable language is Lisp, which was created in 1958. However, **the difference between Lisp and Ruby** is that a programmer who wants to write programs in **Lisp _must be trained in the field of mathematics while programmer who wants to write in Ruby doesn't have to be mathematically-minded_**. This is because **Ruby** is an *imperative programming language*, while **_Lisp isn't_**. In Ruby, you write instructions to the computer in the imperative fashion by explaining to it *HOW* to do something. In Lisp (and other languages such as *Erlang, Haskell, etc.*) you write instructions to the computer by explaining to it *WHAT* needs to get done, and then letting the computer figure out *HOW* to do it.

- Needless to say, it _is much more difficult to master_ languages such as Lisp than it is to master a language such as Ruby.

## When / Why Shall We Use It

Take **a true object-oriented language**, such as Smalltalk.

Drop the _unfamiliar syntax_ and move to _more conventional_, _file-based source code_. Now add in a **_good measure of the flexibility and convenience_** of languages such as Python and Perl.You end up with Ruby. 

Ruby: things such as pure object orientation (**_everything's an object_**), metaclasses, closures, iterators, and ubiquitous heterogeneous collections. Smalltalk users will feel right at home (and C++ and Java users will feel jealous).

At the same time, Perl and Python wizards will find many of their favorite features: **full regular expression support**, tight integration with the underlying operating system, **convenient shortcuts**, and **dynamic evaluation**.

- Ruby **_is easy to learn_**. Everyday tasks are **_simple to code_**, and once you've done them, they are **_easy to maintain and grow._** Apparently difficult things often turn out not to have been difficult after all. Ruby follows the **Principle of Least Surprise**---things work the way you would expect them to, with very few special cases or exceptions. And that really does make a difference when you're programming.

- We _call Ruby a **transparent language**_. By that we mean that Ruby doesn't obscure the solutions you write behind lots of syntax and the need to churn out reams of support code just to get simple things done. With Ruby you write programs _close to the problem domain_. Rather than constantly mapping your ideas and designs down to the pedestrian level of most languages, with Ruby you'll find you can _express them directly and express them elegantly_. This means **you code faster**. It also means your programs stay _readable_ and _maintainable_.

- Using Ruby, we are constantly _amazed_ at _how much code we can write in one sitting_, code that works the first time. There **are very few syntax errors**, **no type violations**, and far **fewer bugs** than usual. This makes sense: there's less to get wrong. _No bothersome semicolons_ to type mechanically at the end of each line. No troublesome type declarations to keep in sync (especially in separate files). No unnecessary words just to keep the compiler happy. *No error-prone framework code*.

- So why learn Ruby? Because we think it will help you program better. It will help you to focus on the problem at hand, with fewer distractions. It will make your life easier

## How To Setup An Environment To Use It On Different Platforms (Windows,Mac,Linux)

### Windows

Go to https://rubyinstaller.org/downloads/

Click to  “=>Ruby+Devkit 2.x.x.-1 (x64)” to Download the most stable version.

If you are using 32 bit version you should download the “x86” version

Run the installition wizard, When you finish

<img src="https://melvinchng.github.io/rails/74.png" width="400">


On the pop up screen _Press_ "1" wait for download , _Press_ "3" and wait for finish.

### Linux

First update the system 

`sudo apt update`

Type 

`apt-get install ruby`

This is going to install the latest version of ruby

When you run `irb` on terminal ruby interpreter is going to start working.

### MAC

MacOS actually comes with a version of Ruby already installed.

## Other Implementations of Ruby
Ruby, as a language, **_has a few different implementations_**. This page has been discussing the reference implementation, in the community often referred to as MRI (“Matz’s Ruby Interpreter”) or CRuby (since it is written in C), but there are also others. They are often useful in certain situations, provide extra integration to other languages or environments, or have special features that MRI doesn’t.

### Here’s a list:

- **JRuby** is Ruby atop the JVM (Java Virtual Machine), utilizing the JVM’s optimizing JIT compilers, garbage collectors, concurrent threads, tool ecosystem, and vast collection of libraries.

- **Rubinius** is ‘Ruby written in Ruby’. Built on top of LLVM, Rubinius sports a nifty virtual machine that other languages are being built on top of, too.

- **TruffleRuby** is a high performance Ruby implementation on top of GraalVM.

- **mruby** is a lightweight implementation of the Ruby language that can be linked and embedded within an application. Its development is led by Ruby’s creator Yukihiro “Matz” Matsumoto.

- **IronRuby** is an implementation “tightly integrated with the .NET Framework”.

- **MagLev** is “a fast, stable, Ruby implementation with integrated object persistence and distributed shared cache”.

- **Cardinal** is a “Ruby compiler for Parrot Virtual Machine” (Perl 6).


## Example Codes

### Some Basic Ruby Codes


- First program
```ruby
  puts "Hello World"
```

- Comments
```ruby
# this is a comment and wont be executed
= begin
this is a multi line
comment in ruby
= end
```

- Simple mathematical functions
```ruby
puts "Alok has #{25+30/6} Rupees in his pocket"
```

- Variables and Names
```ruby
cars = 100
drivers = 30
puts "There are #{cars} cars and #{drivers} drivers."
```

- Getting input
```ruby
print "How old are you ? "
age = gets.chomp
print "How tall are you ?"
height = gets.chomp
puts " You are #{age} year old and your height is #{height} cms"
```

- Prompting people for numbers
```ruby
print "Give a number"
number = gets.chomp.to_i
puts "You just entered #{number}"
```

- Arrays
```ruby
names = Array.new(20)
puts names.size  # This returns 20
puts names.length # This also returns 20
```

- Hashes
```ruby
months = Hash.new( "month" )
puts "#{months[0]}"
puts "#{months[72]}"
```

- If - Else
```ruby
x = 1
if x > 2
   puts "x is greater than 2"
elsif x <= 2 and x!=0
   puts "x is 1"
else
   puts "I can't guess the number"
end
```

- While loop
```ruby
$i = 0
$num = 5

while $i < $num  do
   puts("Inside the loop i = #$i" )
   $i +=1
end
```

- Class , Objects , Methods
```ruby
class Customer 
      
 def initialize(id, name, addr) 
       
# Instance Variables      
 @cust_id = id 
 @cust_name = name 
 @cust_addr = addr 
 end
   
 # displaying result 
 def display_details() 
 puts "Customer id #@cust_id"
 puts "Customer name #@cust_name"
 puts "Customer address #@cust_addr"
 end
end
  
# Create Objects 
cust1 = Customer.new("1", "John", "Wisdom Apartments, Ludhiya") 
cust2 = Customer.new("2", "Poul", "New Empire road, Khandala") 
  
# Call Methods 
cust1.display_details() 
cust2.display_details() 
```

### Some Intresting Things You Can Do With Ruby

- BEGIN & END
```ruby
puts 123
BEGIN {
  puts "Program starting..."
}
```
This code will print "Program starting..." before it prints 123.

- Flip-Flop
```ruby
(1..20).each do |i|
  puts i if (i == 3)..(i == 15)
end
```
This prints all the numbers from 3 to 15, but if you skip 15 it will keep printing.


- Redo Keyword
```ruby
10.times do |n|
  puts n
  redo
end
```
This allows you to repeat the same iteration inside a loop…

- Infinite Nesting of Constants
```ruby
String::String::Fixnum::Float
```
You can have an infinite amount of nested constants like this:

## Things that are specific to Ruby?

- Ruby came into existence as Yukihiro Matsumoto, wanted a scripting language more powerful than Perl, and more object oriented than Python.

- Everything is an _Object_, and all code is executed and has a Self

- Ruby has built in support for Rational numbers and Complex numbers, which helps in solving _complex mathematical problems_.

- Ruby allows code _embedding_. For example, Ruby can be embedded into Hypertext Markup Language (HTML).

- Ruby users can take the advantage of _Dynamic typing_ and _Duck typing_.

- Ruby is often confused with _Ruby on Rails_, which is a server-side framework written in Ruby under the MIT License for implementing web applications.

- Dynamic typing really helps get projects bootstrapped and smooths along changes, especially in the early to middle stages of a project.

- Ruby’s libraries and packages are managed through central library management system called _Rubygems_.

- Ruby has a lot of built features that make reading and _processing files really simple_.

- There are a lot of tasks that are repetitive and lend themselves to creating domain specific languages. Ruby has a _very flexible syntax_ and it has some functional aspects that give you a lot of flexibility in the way that you write your programs. Often, you can wrap up common functionality into a DSL that's suited for your task.



## Resource

https://ruby-doc.org

https://www.ruby-lang.org/en/about/

https://en.wikipedia.org/wiki/Ruby_(programming_language)

https://en.wikipedia.org/wiki/Yukihiro_Matsumoto

https://www.geeksforgeeks.org/ruby-for-beginners/

https://www.tutorialspoint.com/ruby/

https://www.rubyguides.com/2017/02/weird-ruby/
