```
class Muppet

  attr_reader :name, :animal

  def initialize (name, animal)
    @name = name
    @animal = animal
    correct_kermit
  end

  private

  def correct_kermit
    @animal = "frog" if @name == "kermit"
  end

end

kermit = Muppet.new("kermit","monkey")

p kermit
```
