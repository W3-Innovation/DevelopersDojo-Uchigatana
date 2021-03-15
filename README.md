# Developer's Dojo: Uchigatana

<br>

> -   **Homepage:** _https://github.com/W3-Innovation/AjayChambers_
> -   **Repository:** _https://github.com/W3-Innovation/DevelopersDojo-Uchigatana_
> -   **Email Contact:** _AChambers.W3Innovation@Gmail.com_
> -   **Developed By: A Jay Chambers**

<br>
<br>

### <b style="color: #10A0FF">_Version Control Highlighting_</b>

<hr style="background: #0864FF; border: 0px; hieght: 1px;">

<p>Bellow is a Table that charts the colors that Uchigatana asigns to the 3 core statuses used by the VSCode editor: <b>ERROR</b>, <b>WARNING</b>, & <b>INFO</b>. These statuses are used to highlight more areas and items than would be practicle to list here. There are several hooks in the 'VSCode Extension API' that allow extension developers to use these statuses as well, making there use-case limitless, and imposible to document (atleast in theory). Becuase their appearance is quite common throughout VSCode, and VSCode extensions, I found it important to give Uchigatana users a referance to the colors I used for configuring the three statuses. I also listed the configuration that can be used to alter these colors if desired. 
    
<br>

<div style="padding: 20px 30px; margin-left: 12%; background-color: #0000005B; width: 450px;">

| STATUS | BACKGROUND                                                                | FOREGROUND                                                                             | BORDER                                                                    |
| ------ | ------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | ------------------------------------------------------------------------- |
| Error  | <span style=" padding: 4px 18px; background: #FF000F1B;">#FF000F1B</span> | <span style=" padding: 4px 18px; background: #FF7880; color: #000000A5">#FF7880</span> | <span style=" padding: 4px 18px; background: #FF000A50;">#FF000A50</span> |
| Warn   | <span style=" padding: 4px 18px; background: #FFE00E1E;">#FFE00E1E</span> | <span style=" padding: 4px 18px; background: #FFE440; color: #000000A5">#FFE440</span> | <span style=" padding: 4px 18px; background: #FFE40E4E;">#FFE40E4E</span> |
| Info   | <span style=" padding: 4px 18px; background: #38FFA814;">#38FFA814</span> | <span style=" padding: 4px 18px; background: #38FFA8; color: #000000A5">#38FFA8</span> | <span style=" padding: 4px 18px; background: #38FFA850;">#38FFA850</span> |

</div>


<br>
<br>

<p>Uchigatana uses what i consider to be a simi-aggressive highlight when highlighting syntactical errors within the editor. If you are un-happy with the way Uchigatana highlights errors, below are the settings used to custom configure error-highlighting. You can change the colors, and the color's transparancy. Remember though, changing these settings may change the way the editor highlihgts info, warn, & error statuses in other places too, like tab & file names. </p>

```
        {
            // Use the colors setting bellow inside-of your '.vscode/setting.json' file
            // ".../.vscode/settings.json" <-- If you dont know that path research it

            "colors": {
                // -> Editor: 'Error'
                "editorError.background": "#FF000F1B",
                "editorError.foreground": "#FF7880",
                "editorError.border": "#FF000A50",

                // -> Editor: 'Warning'
                "editorWarning.background": "#FFE00E1E",
                "editorWarning.foreground": "#FFE440",
                "editorWarning.border": "#FFE40E4E",

                // -> Editor: 'Info'
                "editorInfo.background": "#38FFA814",
                "editorInfo.foreground": "#38FFA8",
                "editorInfo.border": "#38FFA850",
            },

            // The token bellow changes the foreground of errors inside of the editor.
            "tokenColors": [
                {
                    "scope": "invalid",
                    "settings": {
                        "foreground": "#FF7880",
                        "fontStyle": "italic"
                    }
                },
            ]
    }
```

---

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
