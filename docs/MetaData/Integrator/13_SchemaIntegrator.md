# Schema Integrator
![image](https://user-images.githubusercontent.com/700119/79671562-599c9680-81cb-11ea-8c8c-2443da036d8b.png)

The Schema Integrator is quite simple. Just add one or more valid JSON-LD blocks.
The snippet needs to start with `<script type="application/ld+json">` and has to end with `</script>`. Otherwise, it won't get stored.

## Note!
If a dynamic extractor adds JSON-LD data to the given element, the schema integrator is not able to replace the values!
That said, you need to take extra care implementing additional schema blocks - this could lead to dangerous duplicate entries otherwise! 
