# canvas-os

Custom Linux-based OS distribution building on top of the following projects
- iolinux (defunct, read-only host with apps and roles shared with users, dockable roaming-enabled user-space user environments)
- Canvas (Adds context-based layers on top of your (mostly unstructured) data)
- Canvas UI (electron/neutralino UI overlay + related tools)
- LXC/Docker contianers 
- Locally run LLMs 

```
zroot
    /canvas  
        /OS
            /rootfs
            /etc
            /root
            /var        
            /snapshots                
        /Apps
        /Roles        
        /Runtimes
        /Services
    /home
        /<user>
            /Canvas
                /OS
                /Apps
                /Roles
                /Data
                /Cache

            /Home
                /Desktop
                /Documents
                /Music
                /..
            /Utils
            /Code
            /Work
            /Dotfiles
    /storage
    /network


```
