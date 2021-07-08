Iterating over Hashes

#.each

Iterates over each key/value pair

```
hash = {key1: "value1", key2: "value2"}

hash.each do |key, value|
  puts "#{key}: #{value}"
end
```

Gives you access to key + value on each iteration

.each returns original collection, just like with arrays

#.collect

.collect == .map
we use collect to iterate and then return the altered data
```
birthday_kids = {
    "Timmy" => 9,
    "Sarah" => 6, 
    "Amanda" => 27
}

birthday_kids.collect do |kids_name, age|
    age
end

# => [9, 6, 27]
```
^ notice that the return value was an array of ages, and not the original hash
