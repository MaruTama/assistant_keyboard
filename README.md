# assistant_keyboard

AIスピーカーを用いたqwerty配列キーボードの学習支援アプリケーション

# How to install for rpi_ws281x
pi@raspberrypi:~ $ sudo apt-get update
pi@raspberrypi:~ $ sudo apt-get install build-essential python-dev git scons swig
pi@raspberrypi:~ $ mkdir neo
pi@raspberrypi:~ $ cd neo
pi@raspberrypi:~/neo $ git clone https://github.com/jgarff/rpi_ws281x.git
pi@raspberrypi:~/neo $ cd rpi_ws281x
pi@raspberrypi:~/neo/rpi_ws281x $ scons
pi@raspberrypi:~/neo/rpi_ws281x $ cd python
pi@raspberrypi:~/neo/rpi_ws281x/python $ sudo python3 setup.py install
pi@raspberrypi:~/neo/rpi_ws281x/python $ cd examples/
pi@raspberrypi:~/neo/rpi_ws281x/python $ sudo python3 strandtest.py 

