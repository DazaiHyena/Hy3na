---
layout: default
---

[Link to my github](https://github.com/DazaiHyena).

# Introduction

Featured in this portfolio are multiple lab projects. often times using different virtual machines or physical servers.

## Project 1: Using AWS to Connect to a Windows Instance With Remote Desktop 

This project is a step by step walkthrough of how to create a secure windows instance on AWS and connect to it from any other machine using Remote Desktop.


 1. Create Amazon EC2 instance using a Windows AMI.
 
 2. Select the instance type and either generate a new pem key pair or use an existing key pair.
 
 3. Either create a new firewall security group or create one.
 
 4. Ensure RDP traffic is allowed from anywhere, you can change this if you would like to further restrict who can access       this server.
 
 5. Launch the instance.
 
 6. When the success banner appears, click the instance link.

 7. Highlight the checkbox for the windows instance, select the ACTIONS drop-down, under SECURITY select GET WINDOWS      PASSWORD

 8. Record IP, username, and password.

 9. Open Remote Desktop on any windows machine that you choose, this can be your host machine too

 10. Copy the public DNS to use as the computer name for remote desktop.

 11. Log into Remote Desktop as Administrator using the credentials mentioned previously.

 12. Remote Desktop window will appear.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
