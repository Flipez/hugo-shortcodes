# hugo-shortcodes
## emgithub
Embed code from a file on Github directly into your blog using emgithub.com

### Usage

`{{< emgithub user="flipez" repo="battlesnake" file="src/battlesnake/point.cr" >}}`

|Parameter |Default  |Required|
|----------|---------|:------:|
|`user`    |""       |y       |
|`repo`    |""       |y       |
|`file`    |""       |y       |
|`branch`  |"master" |n       |
|`style`   |"dracula"|n       |
|`lines`   |"false"  |n       |
|`metadata`|"false"  |n       |
|`border`  |"false"  |n       |
