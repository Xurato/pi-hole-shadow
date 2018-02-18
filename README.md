# pi-hole-shadow
Custom theme for [pi-hole](https://pi-hole.net/) admin webinterface

[![Screenshot](https://i.imgur.com/y1u2WyO.png)](https://i.imgur.com/y1u2WyO.png)
---

## Install
Type the following commands into SSH, line by line.

```
cd /var/www/html/admin/style/vendor/
sudo git clone https://github.com/Xurato/pi-hole-shadow.git
sudo rm -f skin-blue.min.css
sudo cp pi-hole-shadow/skin-blue.min.css .
sudo rm -rf pi-hole-shadow
```
Don't forget the trailing " ." on the cp line (it means copy to current directory).

## Uninstall
Type the following commands into SSH, line by line.

```
cd /var/www/html/admin/style/vendor/
sudo git reset --hard
```

---

### License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
