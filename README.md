# perlin.rb
 Ruby Referrence Implementation of Perlin Noise


## Example
 Example ruby program to generate a 3D Perlin Noise.

```ruby
require './src/perlin.rb'

generator = perlin.new # initialize the class

noise = generator.noise(x, y, z) # generate the noise

puts noise
```