# sublime-text

## Paso 1:
Buscar el terminal en el buscador y ejecutarlo

## Paso 2:
copiar el link y pegarlo en el terminal
```
sudo apt-get upgrade
```
despues poner la contraseña y darle a enter

## Paso 3:
copiar el link y pegarlo en el terminal 
```
wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -
```
## Paso 4:
```
sudo apt-get install apt-transport-https
```

## Paso 5:
```
echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list
```

## Paso 6:
```
sudo apt update
```

## Paso 7:
```
sudo apt install sublime-text
```

## Paso 8:
ir al buscador y poner sublime
