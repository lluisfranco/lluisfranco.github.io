# OUI Samples post


## Title 2

### Samples

[99]/[100]

Gone camping! :(fas fa-campground fa-fw): Be back soon...

That is so funny! :(far fa-grin-tears):

Hi, everyone! :)

### Shortcodes

Figure / image
{{< figure src="/images/posts/cover.jpg" title="Mountains (figure)" >}}

Gist
{{< gist spf13 7896402 >}}

Code
{{< highlight html >}}
<section id="main">
    <div>
        <h1 id="title">{{ .Title }}</h1>
        {{ range .Pages }}
            {{ .Render "summary"}}
        {{ end }}
    </div>
</section>
{{< /highlight >}}

Instagram example:
{{< instagram BWNjjyYFxVx hidecaption >}}

Twitter example:
{{< tweet 1245963210735353861 >}}

Vimeo
{{< vimeo 146022717 >}}

Youtube
{{< youtube w7Ft2ymGmfc >}}

Eof f

