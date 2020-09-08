# Variables
Learn how to use variables and strings!!


A variable is a storage container for a variable. What does that mean? It means that it represents whatever value you give it! This allows you to change the value, while keeping the variable itself the same. Let's look at an example:

  ```
  name = 'Sarah'
  print(name)
  ```
In this case, the name 'Sarah' will be printed to your console. You declare that the *variable* called name is equal to the *value* Sarah.

# Strings

By definition, a string is an array of characters. A character is a letter, number or symbol. Basically, anything on your keyboard can be considered a character *as long as it is in between double or single quotes.* Strings behave differently to integer or float data types, which behave like typical numbers. For example,

```
print(2+2)

```
will print "4" to the console. Both numbers behave as numbers, and so you can do math to them. However, if you typed out

```
print("2+2")
```
then "2+2" will print to the console beacuse "2+2" is a string datatype.

# Adding Strings

You can add strings together! Take this example:

```
print("Hello," + " everyone!")
```
This will print "Hello, everyone! to the console. Let's say you wanted to add together a string and a string variable, it would look something like this:

```
name = "Sarah"
print("Hello, "+ name + "!")
```
Now if I want to change the name, all I would need to do is change the value of the variable. This is *especially* helpful when I use the variable many times. For example, if I had a block of code that looked like this:

```
name= "Sarah"

print(name + ", how old are you?")
print(name + ", when is your birthday?")
print("My best friend's name is " + name + " too!")
print("Wow, " + name + " you are so cool!")
```
All I would need to do is change the value "Sarah" to a different name one time in the "name=" line (also known as the variable creation statement), and the name will change for each line of code!
