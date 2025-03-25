puts 'Hello Ruby'

#single line comment

=begin
This is a
multi-line comment
=end


#variables and assignments
name="Chinmaya"
age=19
is_student=true


puts 4+10

#control flow
x=10


#Arrays
fruits=['Apple','Banana']
puts fruits[0]


#Hash
person={name:'Chinmaya',age:19}
puts person[:name]


#find array methods
[1,2].methods


#find has methods
{name:"chinmaya"}.methods

#if-else
age=20
if age<=18
  puts 'less than 18'
else
  puts 'greater than 18'
end


fruits=["Apple","Banana"]
fruits.each{|fruit|}
fruits.each{puts fruits}
