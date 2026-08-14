# Drillas CS:GO FastDL
FastDL repository for CS:GO maps, models, materials, and sounds.

### How to use with GitHub Pages:
1. Go to repository **Settings** -> **Pages**.
2. Set Source to **Deploy from a branch** -> `main` / `root`.
3. In `server.cfg`, set:
   ```ini
   sv_allowdownload 1
   sv_allowupload 0
   sv_downloadurl "https://<your-username>.github.io/drillas-fastdl/csgo"
   ```
