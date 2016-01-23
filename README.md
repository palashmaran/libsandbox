Sandbox library with statically  linked system calls  to avoid restricted function.
INSTALLATION

  Note, there is no need to install 32bit packages on x86_64 systems. The 64bit 
  libsandbox and pysandbox can handle both 32bit and 64bit binary programs.

  source packages
  
  $ git clone https://github.com/palashmaran/libsandbox.git
  
  for c/c++
  
  $ cd libsandbox/Sandbox/libsandbox
  
  $ ./configure
  
  $ sudo make install
  
  $ sudo ldconfig  
  
  
  for python
  
  $ cd  libsandbox/Sandbox/pysandbox
  
  $ python setup.py build
  
  $ sudo python setup.py install
  
  $ sudo ldconfig    

GETTING STARTED
  
  The simplest way to get started with the sandbox libraries is to invoke the 
  Python

    $ python sample2.py "exe name"

  for ex  : $ python sample2.py testing

To invoke sandbox by c program
    $ ./sandbox  testing
    
  output : 
  hello
  result: OK
  cpu: 2ms
  mem: 4292kB


    if u  get above output means sandbox is working fine ;



(optional)   Compilation steps for cSandbox.c
    gcc -o sandbox cSandbox.c -lsandbox

   if you face any error then set permissions 777  for in case of c  cSandbox.c,sandbox or in case of python  sample2.py then check 
    

  if setup sandboxing in php environment and still facing problem then set ownership to www-data and set permission 777 to  /var/www/html .
