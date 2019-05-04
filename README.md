## `Stopping Spam JavaScript Method` 

### CODE BLOCK 1

```
<script type="text/javascript">
    function gen_mail_to_link(lhs,rhs,subject) {
        document.write("<a href=\"mailto");
        document.write(":" + lhs + "@");
        document.write(rhs + "?subject=" + subject + "\">" + lhs + "@" + rhs + "<\/a>");
    }
</script>

```

### CODE BLOCK 2

```
<script type="text/javascript">

gen_mail_to_link('example','gmail.com','Subject'); 

</script>

<noscript>

<em>Email address protected by JavaScript.</em>

</noscript>
```
