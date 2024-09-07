# switch

This scripts helps you run mosquitto mqqt broker or thingsboard service locally without getting errors as both service utilizes same mqqt port and you'll have to stop one befor using the other


since you're here i assume that you are tired of compiling your codes with up to three lines of command before seeing an error or testing your program

This is a custom script that helps automate that boring process of hitting your keyboard over and over again to do the same task and thus saves time.

And guess what !!!

- you can invoke this script from any directory you're working on

## Installation

```
git clone https://github.com/n1lby73/switch
cd switch
sudo bash install.sh
```
## Uninstall

To uninstall switch simply type the below command anywhere in your terminal

```
uninstall_switch
```

## Usage

To permit thingsboard local server to start running on pc use:

```
switch thingsboard
```

To permit mosquitto local server to start running on pc use:

```
switch mosquitto
```

## Support and bug reporting
- Report found bugs [here](https://github.com/n1lby73/switch/issues)
- Contributions, issues, and feature requests are welcome!
- Feel free to make PR
- Give a ★ if you like this project!

## License

[GNU V3](https://github.com/n1lby73/switch/blob/main/LICENSE)
