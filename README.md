# IMPLEMENTING-FILES-CONCEPT
file = &quot;sample.txt&quot;
with open(file, &quot;w&quot;) as f:
f.write(&quot;Python is easy to learn.\n&quot;)
f.write(&quot;File handling is important.\n&quot;)
with open(file, &quot;a&quot;) as f:
f.write(&quot;Practice makes perfect.\n&quot;)
with open(file, &quot;r&quot;) as f:
text = f.read()
print(&quot;File Content:\n&quot;, text)
print(&quot;Lines:&quot;, text.count(&quot;\n&quot;))
print(&quot;Words:&quot;, len(text.split()))
print(&quot;Characters:&quot;, len(text))
print(&quot;Python count:&quot;, text.count(&quot;Python&quot;))

Output:
File Content:
Python is easy to learn.
File handling is important.
Practice makes perfect.
Lines: 3
Words: 12
Characters: 77
Python count: 1
