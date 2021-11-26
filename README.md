# html-ref

### Download via link (donwload attr)

`<a href="img/img.png" download >Download image</a>`

### built in drop menu

```
<!-- <details __open__> to make it open by default. To style arrow color use details::marker { color: red; } -->
        <details>
            <summary>Data</summary>
            <p>text</p>
        </details>

```

### buit in input search dropdown

```
        <div>
            <input type="text" list="list1">
            <datalist id="list1">
                <option value="value 1" />
                <option value="value 2" />
            </datalist>
        </div>
```

### fieldset and legend

```
    <fieldset>
        <legend>Title</legend>
        <p></p>
    </fieldset>
```
### additional attributes for inputs (visible on mobile only && newest versions of browser)

```
 enterkeyhint=""
        enter
        done
        go
        next
        previous
        search
        send
```

### :focus-within selector

check focus-within.html and corresponding styles

When children element has focus - __:focus-within__ (if it is set on the parent) - trigers
full text from this repo (outer): https://gist.github.com/prof3ssorSt3v3/7cf96e740e470ab87bfa637faeb7a83b
