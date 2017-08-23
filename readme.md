puts "Hello, World!"
# puts "Hello, Wyncode!"
p "Hello, The LAB!"
ruby pyramid.rb 5
height = ARGV[0]
output = ""
height.times do |i|
  output << "*" * i
  output << "\n"
end
puts output
