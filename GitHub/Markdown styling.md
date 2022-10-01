# Add styles
You CAN NOT add CSS to Github .md files.  
But you can add svg with foreignObject in it that include styling and html code.

example.svg
```svg
<svg fill="none" viewBox="0 0 400 400" width="400" height="400" xmlns="http://www.w3.org/2000/svg">
    <foreignObject width="100%" height="100%">
        <div xmlns="http://www.w3.org/1999/xhtml">
            <style>
            h1 {
                color: red;
                animation: mymove 2s infinite;
            }

            @keyframes mymove {
                from {
                    color: red;
                }
                to {
                    color: yellow;
                }
            }
            </style>
            <h1>HELLO WORLD!</h1>
        </div>
    </foreignObject>
</svg>
```

README.md
```md
# My GitHub README

Welcome to my README!

<div align="center">
    <img src="example.svg" width="400" height="400" alt="css-in-readme">
</div>
```
[Working example](https://github.com/sindresorhus/css-in-readme-like-wat)


Based on [StackOverflow](https://stackoverflow.com/questions/51956361/custom-css-file-for-readme-md-in-a-github-repo)

# Show md as webpage