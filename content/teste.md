---
draft: true

---

{{< alert >}}
**Warning!** This action is destructive!
{{< /alert >}}

{{< alert "x-twitter" >}}
Don't forget to [follow me](https://x.com/jpanther) on X.
{{< /alert >}}

{{< badge >}}
New article!
{{< /badge >}}
{{< chart >}}
type: 'bar',
data: {
  labels: ['Tomato', 'Blueberry', 'Banana', 'Lime', 'Orange'],
  datasets: [{
    label: '# of votes',
    data: [12, 19, 3, 5, 3],
  }]
}
{{< /chart >}}

{{< figure
    src="abstract.jpg"
    alt="Abstract purple artwork"
    caption="Photo by [Jr Korpa](https://unsplash.com/@jrkorpa) on [Unsplash](https://unsplash.com/)"
    >}}

<!-- OR -->

![Abstract purple artwork](abstract.jpg "Photo by [Jr Korpa](https://unsplash.com/@jrkorpa) on [Unsplash](https://unsplash.com/)")


{{< icon "github" >}}

{{< katex >}}
\\(f(a,b,c) = (a^2+b^2+c^2)^3\\)
{{< lead >}}
When life gives you lemons, make lemonade.
{{< /lead >}}
{{< mermaid >}}
graph LR;
A[Lemons]-->B[Lemonade];
B-->C[Profit]
{{< /mermaid >}}
{{< profile align="center" >}}




```html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
```
{{< highlight html >}}
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
{{< /highlight >}}
