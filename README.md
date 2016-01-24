Sandbox library with statically  linked system calls  to avoid restricted function.
INSTALLATION

  Note, there is no need to install 32bit packages on x86_64 systems. The 64bit 
  libsandbox and pysandbox can handle both 32bit and 64bit binary programs.
  
  binary packages (CentOS/RedHat)
  
  $ yum install --nogpgcheck libsandbox-<version>.<platform>.rpm
  $ yum install --nogpgcheck pysandbox-<version>.<platform>.rpm
  
  binary packages (Ubuntu)
  
  $ dpkg -i libsandbox_<version>_<platform>.deb
  $ dpkg -i pysandbox_<version>_<platform>.deb
  
  source packages
  
  $ tar -xzf libsandbox-<version>.tar.gz
  $ cd libsandbox-<version>
  $ ./configure
  $ sudo make install
  
  $ tar -xzvf pysandbox-<version>.tar.gz
  $ cd pysandbox-<version>
  $ python setup.py build
  $ sudo python setup.py install

GETTING STARTED
  
  The simplest way to get started with the sandbox libraries is to invoke the 
  Python

    $ python sample2.py

    
