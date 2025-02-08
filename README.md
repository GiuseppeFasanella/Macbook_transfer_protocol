# Macbook_transfer_protocol
Starter pack when you init a new Macbook PC

get brew (used to install package)
```
brew install --cask anaconda
## you might need to export the path: export PATH="/opt/homebrew/anaconda3/bin:$PATH"
brew install vscodium
brew install yt-dlp
brew upgrade yt-dlp
ffmpeg
pdftk-java
imagemagick
pandoc
```

Install dropbox-cli (utile per synchare - desynchare da terminale)
```
mkdir -p ~/bin
echo 'export PATH="$HOME/bin:$PATH"' >> ~/.zshrc
source ~/.zshrc

curl -Lo ~/.dropbox-cli "https://www.dropbox.com/download?dl=packages/dropbox.py"
chmod +x ~/.dropbox-cli
mv ~/.dropbox-cli ~/bin/dropbox

dropbox status ## you might need to restart your pc
```


## Things to understand
e per gli schermi? (io ne ho 2) --> Se i 2 schermi sono entrambi sull'hub NON li usa entrambi. Soluzione: uno schermo sull'hub e un altro pluggato nella presa HDMI del mac

perché drag and drop sull'HD non funziona? --> credo sia questione di formattazione
