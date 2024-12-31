#### cp fonts
```sh
sudo cp -r JetBrainsMono ~/.local/share/fonts
sudo cp -r Sauce\ Code\ ~/.local/share/fonts
sudo cp -r FiraCode ~/.local/share/fonts
```

#### fc
```sh
fc-cache -fv
fc-list :lang=zh-cn | grep simsun
fc-list :lang=en | grep pala
```
