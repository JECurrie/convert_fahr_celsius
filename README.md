# convert_fahr_celsius
#Convert fahrenheit to celsius.
def convert!( fahrenheit )
  celsius = ( fahrenheit - 32 )/ 1.8000
  puts format( "%.2f", celsius )
# puts (celsius*100).round/100.00
end

puts convert!( 32 ) #212 )
