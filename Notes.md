Iterating over Hashes

.each

Iterates over each key/value pair

```
hash = {key1: "value1", key2: "value2"}

hash.each do |key, value|
  puts "#{key}: #{value}"
end
```

Gives you access to key + value on each iteration

.each returns original collection, just like with arrays
