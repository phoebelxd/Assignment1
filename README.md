# Assignment1
  1  passwd
    2  exit
    3  who
    4  vim
    5  where
    6  which
    7  which ls
    8  ls
    9  ls -a
   10  cp .bashrc .bashrc.orig
   11  ls
   12  ls-a
   13  ls -a
   14  vim .bashrc
   15  exit
   16  which exit
   17  which logout
   18  mkdir bin
   19  ls
   20  ls -l
   21  echo path
   22  echo $path
   23  echo $PATH
   24  vim .bashrc
   25  echo $PAGER
   26  vim .bashrc
   27  ls /usr/bin
   28  vim .bashrc
   29  exit
   30  echo $HAHA
   31  vim .bashrc
   32  exit
   33  echo $HAHA
   34  vim .bashrc
   35  exit
   36  echo $PATH
   37  ls/home
   38  ls /home
   39  cd /usr/bin
   40  cd /usr
   41  ls
   42  cd /
   43  ls
   44  cd /home
   45  ls
   46  cd xianghui/
   47  cd xianduli
   48  cd ~
   49  pwd
   50  history
   51  mkdir history
   52  history > ~/history/history.txt
   53  cd history
   54  ls
   55  vim history.txt 
   56  cat history.txt 
   57  :q
   58  vim .bashrc
   59  cd ..
   60  pwd
   61  cd history
   62  pwd
   63  ..
   64* es
   65  exit
   66  cd history
   67  cat history.txt 
   68  history
   69  vim. bashrc
   70  cd home
   71  cd..
   72  cd ..
   73  vim .bashrc
   74  which history
   75  cat .bash_history
   76  vim .bashrc
   77  exit
   78  cd history
   79  ls
   80  cat
   81  cat history
   82  cat history.txt
   83  cd ~
   84  cat history/history.txt
   85  cat /~/history/history.txt
   86  cat /~
   87  cat /~/history
   88  cat ~/.bashrc
   89  cat ~/history/tistory.txt
   90  cat ~/history/history.txt
   91  cd /usr/bin
   92  cat ~/history/history.txt
   93  cat ../../history/history.txt
   94  ..
   95  cd ~
   96  ..
   97  cd bin/usr
   98  cd usr/bin
   99  cat ..
  100  cd ..
  101  cd usr/bin
  102  cd bin
  103  cat ../../home/xianduli/history/history.txt 
  104  which bash
  105  help
  106  ls
  107  which ls
  108  ls ls
  109  ls ls -l
  110  ls
  111  exit
  112  cat history.txt
  113  cat history
  114  cd history
  115  ls
  116  cat history.txt
  117  vim .bashrc
  118  cd usr/bin
  119  cd bin
  120  cd bin/usr
  121  cd ..
  122  ls
  123  cd bin
  124  ls
  125  ls-l
  126  ls -l
  127  vim .bashrc
  128  ..
  129  vim .bashrc
  130  which path
  131  cd path
  132  cat path
  133  echo $path
  134  echo $PATH
  135  cd history
  136  cat history.txt
  137  ..
  138  vim .bashrc
  139  echo $PATh
  140  echo $PATH
  141  vim .bashrc
  142  cd ~
  143    perl -MNet::FTP -e     '$ftp = new Net::FTP("ftp.ncbi.nlm.nih.gov", Passive => 1);
  144       $ftp->login; $ftp->binary;
  145       $ftp->get("/entrez/entrezdirect/edirect.tar.gz");'
  146    gunzip -c edirect.tar.gz | tar xf -
  147    rm edirect.tar.gz
  148    builtin exit
  149    /bin/bash
  150    export PATH=${PATH}:$HOME/edirect >& /dev/null || setenv PATH "${PATH}:$HOME/edirect"
  151    ./edirect/setup.sh
  152  ls
  153  cd edirect
  154  ls
  155  cd ~
  156    perl -MNet::FTP -e     '$ftp = new Net::FTP("ftp.ncbi.nlm.nih.gov", Passive => 1);
  157       $ftp->login; $ftp->binary;
  158       $ftp->get("/entrez/entrezdirect/edirect.tar.gz");'
  159    gunzip -c edirect.tar.gz | tar xf -
  160    rm edirect.tar.gz
  161    builtin exit
  162    /bin/bash
  163    export PATH=${PATH}:$HOME/edirect >& /dev/null || setenv PATH "${PATH}:$HOME/edirect"
  164  exit
  165  esearch -db pubmed -query "lycopene cyclase" |   efetch -format abstract
  166  ls
  167  mv edirect/* bin
  168  esearch -db pubmed -query "lycopene cyclase" |   efetch -format abstract
  169  echo $PATH
  170  echo $PS1
  171  esearch -db pubmed -query "lycopene cyclase" |   efetch -format abstract > pubmed.090819.v1.txt
  172  wordcloud_cli
  173  pip install wordcloud
  174  pip install wordcloud --usr
  175* 
  176  wordcloud_cli
  177  wordcloud_cli --text pubmed.090819.v1.txt --imagefile wordcloud.png
  178  esearch -db pubmed -query "Myotonic Dystrophy" |   efetch -format abstract > pubmed.090819.v1.txt
  179  vim pubmed.090819.v1.txt 
  180  ls -lh
  181  esearch 
  182  esearch -h
  183  esearch -h | more
  184  esearch -db pubmed -days 100 -query "Myotonic Dystrophy" |   efetch -format abstract > pubmed.090819.v1.txt
  185  ls -lh
  186  esearch -h
  187  vim pubmed.090819.v1.txt 
  188  wordcloud_cli --text pubmed.090819.v1.txt --imagefile wordcloud.png
  189  git clone https://github.com/phoebelxd/Assignment1
  190  cd Assignment1
  191  ls 
  192  ..
  193  ls 
  194  mv wordcloud.png Assignment1/assignment1.wordcloud.png
  195  ls
  196  cd Assignment1/
  197  ls
  198  git info
  199  git log
  200  git status
  201  git add *
  202  git commit
  203  git config --global user.email "you@example.com"
  204    git config --global user.name "Your Name"
  205  git config --global user.email "xianduli@usc.edu"
  206  git config --global user.name "Phoebelxd"
  207  git commit
  208  git push
  209  wordcloud_cli --help
  210  ..
  211  wget https://www.heartfoundation.org.au/images/uploads/main/heart-img.png
  212  wordcloud_cli --text pubmed.090819.v1.txt --colormask file heart-img.png --imagefile assignment1.wordcloud.png
  213  wordcloud_cli --text pubmed.090819.v1.txt --colormask  heart-img.png --imagefile assignment1.wordcloud.png
  214  wget https://www.heartfoundation.org.au/images/uploads/main/heart-img.pnghttps://cdn.prod-carehubs.net/n1/802899ec472ea3d8/uploads/2017/02/a-watercolor-graphic-of-a-heart-in-pinks-and-purples-special-crop-1024x864.jpg
  215  wget https://cdn.prod-carehubs.net/n1/802899ec472ea3d8/uploads/2017/02/a-watercolor-graphic-of-a-heart-in-pinks-and-purples-special-crop-1024x864.jpg
  216  ls
  217  rm heart-img.png 
  218  ls
  219  mv a-watercolor-graphic-of-a-heart-in-pinks-and-purples-special-crop-1024x864.jpg m.jpg
  220  wordcloud_cli --text pubmed.090819.v1.txt --colormask m.jpg --imagefile assignment1.wordcloud.png
  221  mv assignment1.wordcloud.png Assignment1/
  222  cd Assignment1/
  223  git commit -m "Update"
  224  git push
  225  git log
  226  ls
  227  ls -lh
  228  git status
  229  git add *
  230  git status
  231  git commit -m "Update"
  232  git push
  233  wordcloud_cli --text pubmed.090819.v1.txt --colormask m.jpg --width 1024 --height 864 --background "#fff" --imagefile assignment1.wordcloud.png
  234  ..
  235  wordcloud_cli --text pubmed.090819.v1.txt --colormask m.jpg --width 1024 --height 864 --background "#fff" --imagefile assignment1.wordcloud.png
  236  mv assignment1.wordcloud.png Assignment1/
  237  cd Assignment1/
  238  git add *
  239  git commit -m "Update"
  240  git push
  241  ..
  242   history
