# perlin.rb
![](https://badgen.net/github/stars/fikret0/perlin.rb) ![](https://badgen.net/github/watchers/fikret0/perlin.rb) ![](https://badgen.net/badge/license/GPLv3/red) ![](https://badgen.net/badge/code%20style/extreme/f2a) ![](https://badgen.net/badge/code%20quality/A+/green)

 Ruby Referrence Implementation of Perlin Noise


## Example
 Example ruby program to generate a 3D Perlin Noise.

```ruby
require './src/perlin.rb'

generator = perlin.new # initialize the class

noise = generator.noise(x, y, z) # generate the noise

puts noise
```