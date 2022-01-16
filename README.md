# AutoRotateScreen
Um script Python para fornecer recursos de rotação automática para laptops 2 em 1 no Linux

<div align="center"><a href="https://www.youtube.com/watch?v=lVW6cMOrwZ0" target="_blank"><img src="Video.gif" ></a></div>
<p align="center"><a href="https://www.youtube.com/watch?v=lVW6cMOrwZ0" target="_blank">Click on gif to see full video</a></p>


Este script usa **iio-sensor-proxy** para ler os ângulos de inclinação e rotação da tela e define a orientação desejada usando **xrandr**. Instale esses programas se eles ainda não estiverem incluídos para que isso funcione.


Mudar nome da variavel 'touchpad' para o nome da sua touch screen (use **xinput list** para ver os nomes)

Se sua tela continuar invertida, tente trocar os valores da variavel 'state'

Configurações > Painel de definiçãoes > aplicações > laçadores de aplicações pessoais. Adicione o caminho da arquivo **AutoRotateScreen.py** e adicione a imagem **download.png**.
Adicione o aplicativo em sua barra de tarefas e toda vez que precisar rotacionar a sua tela é só clicar no item 

<img src="captura de tela.jpg" ></a></div>