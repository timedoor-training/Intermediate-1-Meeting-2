# Timedoor Training Teen
## Intermediate A - Meeting 2

Pertemuan 2 mempelajari cara menarik file dari github dan number generator, starter kit project terdapat pada link berikut:

>https://github.com/timedoorAcademy-smp/Meeting4-Project3



###  HTML Code Basic

```html
<body>
    <b> Natural Number Sequence <br></b>
    <label for="input_stop">Enter Any Number</label>
    <input type="number" id="input_stop">
    <button onclick="sequence()">Submit</button>

</body>
```

### Javascript Basic
```html
    <script>
        sequence = () => {
            var stop = Number(document.getElementById("input_stop").value)
            for (var i = 0; i < stop; i++) {
                document.write(i)
                document.write("<br>")
            }
        }
    </script>
```

## Challenge



### Javascript Challenge
```html
    <script>
        sequence = () => {
            var stop = Number(document.getElementById("input_stop").value)
            for (var i = 0; i < stop; i++) {
                // ganti i dengan nama (ex: timedoor)
                document.write("Timedoor") 
                document.write("<br>")
            }
        }
    </script>
```

