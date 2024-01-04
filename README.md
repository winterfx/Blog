# Blog
- Architecture
    - github page
    - hugo
- Theme
    - PaperMod
- Operation

    1. create a new page
    ```bash
    hugo new posts/{your-new-artical}.md
    ```
    2. testing in local
    ```bash
    hugo server --buildDrafts --buildFuture --port=8080
    ```
    3. push page to remote repo
    - old
        ```bash
        hugo
        git add .
        git commit -m "xxx"
        git push
        cd public && git pull --rebase origin main 
        git add .
        git commit -m "sync"
        git push origin main && cd ..
        ```
    - new
        git action
        