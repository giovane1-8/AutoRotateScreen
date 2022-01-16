# AutoRotateScreen
Um script Python para fornecer recursos de rotação automática para laptops 2 em 1 no Linux


Este script usa **iio-sensor-proxy** para ler os ângulos de inclinação e rotação da tela e define a orientação desejada usando **xrandr**. Instale esses programas se eles ainda não estiverem incluídos para que isso funcione.

Mudar nome da variável 'touchpad' para o nome da sua touchscreen (use **xinput list** para ver os nomes)

Se sua tela continuar invertida, tente trocar os valores da variável 'state'

Configurações > Painel de definições > aplicações > laçadores de aplicações pessoais. Adicione o caminho do arquivo **AutoRotateScreen.py**, escreva python3 no início e de um espaço e adicione a imagem **download.png**.
Adicione o aplicativo em sua barra de tarefas e toda vez que precisar rotacionar a sua tela é só clicar no item 

<img src="captura de tela.jpg" ></a></div>