    1  clear
    2  sudo apt-get update
    3  sudo apt-get install ca-certificates curl
    4  sudo install -m 0755 -d /etc/apt/keyrings
    5  sudo curl -fsSL https://download.docker.com/linux/ubuntu/gpg -o /etc/apt/keyrings/docker.asc
    6  sudo chmod a+r /etc/apt/keyrings/docker.asc
    7  echo   "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.asc] https://download.docker.com/linux/ubuntu \
    8    $(. /etc/os-release && echo "${UBUNTU_CODENAME:-$VERSION_CODENAME}") stable" |   sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
    9  sudo apt-get update
   10  sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
   11  sudo apt-get update
   12  sudo docker run hello-world
   13  docker run hello-world
   14  sudo docker container ls
   15  sudo docker container ls -a
   16  sudo groupadd docker
   17  sudo usermod -aG docker $USER
   18  exit
   19  docker container ls
   20  clear
   21  docker container ls
   22  docker run hello-world
   23  docker container ls
   24  docker container ls -a
   25  docker container delete 5db986992689
   26  docker container remove 5db986992689
   27  docker container remove dca
   28  cls
   29  clear
   30  sudo systemctl enable docker.service
   31  sudo systemctl enable containerd.service
   32  sudo apt-get update
   33  sudo apt-get install -y apt-transport-https ca-certificates curl gnupg
   34  curl -fsSL https://pkgs.k8s.io/core:/stable:/v1.33/deb/Release.key | sudo gpg --dearmor -o /etc/apt/keyrings/kubernetes-apt-keyring.gpg
   35  sudo chmod 644 /etc/apt/keyrings/kubernetes-apt-keyring.gpg # allow unprivileged APT programs to read this keyring
   36  echo 'deb [signed-by=/etc/apt/keyrings/kubernetes-apt-keyring.gpg] https://pkgs.k8s.io/core:/stable:/v1.33/deb/ /' | sudo tee /etc/apt/sources.list.d/kubernetes.list
   37  sudo chmod 644 /etc/apt/sources.list.d/kubernetes.list
   38  sudo apt-get update
   39  sudo apt-get install -y kubectl
   40  ls
   41  ls -a
   42  kubectl cluster-info
   43  wget -q -O - https://raw.githubusercontent.com/k3d-io/k3d/main/install.sh | bash
   44  sudo wget -q -O - https://raw.githubusercontent.com/k3d-io/k3d/main/install.sh | bash
   45  k3d --help
   46  clear
   47  k3d cluster create meucluster --servers 1
   48  k3d cluster remove meucluster
   49  k3d cluster delete meucluster
   50  clear
   51  k3d cluster create meucluster --servers 2 --agents 2
   52  kubectl cluster-info
   53  clear
   54  kubectl get nodes
   55  kubectl get pods
   56  mkdir aulas
   57  cd aulas
   58  ls
   59  sudo apt update
   60  sudo apt install git -y
   61  git --version
   62  git config --global user.name "Fabio Rosa"
   63  git config --global user.email "josefabiorosa@gmail.com"
   64  git config --list
   65  ssh-keygen -t ed25519 -C "josefabiorosa@gmail.com"
   66  ls ~/.ssh
   67  eval "$(ssh-agent -s)"
   68  ssh-add ~/.ssh/id_ed25519
   69  v
   70  cat ~/.ssh/id_ed25519.pub
   71  ssh -T git@github.com
   72  git clone git@github.com:josefabiorosa/kube-news.git
   73  ls
   74  git clone git@github.com:josefabiorosa/fake-shop.git
   75  git clone git@github.com:josefabiorosa/conversao-distancia.git
   76  git clone git@github.com:josefabiorosa/conversao-temperatura.git
   77  git clone https://github.com/josefabiorosa/simulador-do-caos.git
   78  git clone git@github.com:josefabiorosa/desafio-devops-cloud.git
   79  ls
   80  code .
   81  k3d cluster list
   82  k3d cluster delete meucluster
   83  clear
   84  lsblk
   85  cd /mnt/
   86  ls
   87  cd c
   88  ls
   89  sudo 
   90  sudo su
   91  exit
   92  sudo -1
   93  sudo su
   94  nano /etc/hosts
   95  sudo su
   96  exit
   97  clear
   98  sudo su
   99  docker container ls
  100  exit
  101  docker container ls
  102  cd /mny
  103  cd /mnt
  104  ls
  105  cd e
  106  ls
  107  cd ..
  108  cd c
  109  ls
  110  cd wsl_temp_distro/
  111  ls
  112  cd ..
  113  ls
  114  exit
  115  ls
  116  exit
  117  cd aulas
  118  ls
  119  cd /mnt/c/Users/Fabio
  120  ls
  121  cd .. 
  122  ls
  123  cd aula_old
  124  ls
  125  cd aula
  126  ls
  127  clear
  128  ls /home/fabio
  129  /aulas
  130  ls /home/fabio/aulas
  131  clear
  132  ls
  133  cp -R . /home/fabio/aulas
  134  cd /home/faboi
  135  cd /home/fabio
  136  cd aulas
  137  ls
  138  cd kube-news/
  139  ls
  140  cd ..
  141  cd fake-shop/
  142  l
  143  ls
  144  cd src
  145  ls
  146  cd ..
  147  ls
  148  cd argocd
  149  ls
  150  cd ..
  151  ls
  152  cd argocd/
  153  ls
  154  clear
  155  exit
  156  cd aulas
  157  ls
  158  exit
  159  code .
  160  cd /mnt/c/users/fabio
  161  ls
  162  cd .ssh
  163  ls
  164  cp * /home/fabio/.ssh/
  165  ls ~/.ssh
  166  cd ..
  167  cd ~/
  168  cd /ssh
  169  cd /.ssh
  170  cd .ssh
  171  ls
  172  eval "$(ssh-agent -s)"
  173  ssh-add ~/.ssh/id_ed25519
  174  cat ~/.ssh/id_ed25519.pub
  175  ssh -T git@github.com
  176  ls
  177  rm *
  178  ls
  179  clear
  180  ssh-keygen -t ed25519 -C "josefabiorosa@gmail.com"
  181  ls
  182  eval "$(ssh-agent -s)"
  183  ssh-add ~/.ssh/id_ed25519
  184  cat ~/.ssh/id_ed25519.pub
  185  ssh -T git@github.com
  186  apt install vscode
  187  sudo apt install vscode 
  188  code .
  189  cd ..
  190  cd aulas
  191  ls
  192  cd kube-news/
  193  ls
  194  code .
  195  cd ..
  196  cd conversao-temperatura/
  197  code .
  198  cd ..
  199  cd conversao-distancia/
  200  ls
  201  code .
  202  ls
  203  clear
  204  docker container ls
  205  docker container ls -a
  206  docker image ls
  207  ls
  208  cat Dockerfile 
  209  docker build -f josefabiorosa/josefabiorosa/conversao-temperatura .
  210  docker build -f josefabiorosa/conversao-temperatura .
  211  docker build -t josefabiorosa/conversao-temperatura .
  212  docker image ls
  213  docker push josefabiorosa/conversao-temperatura:teste
  214  docker push josefabiorosa/conversao-temperatura
  215  docker login
  216  docker push josefabiorosa/conversao-temperatura
  217  exit
  218  ls
  219  cd aulas
  220  ls
  221  . code
  222  gemini
  223  clear
  224  exit
  225  code .
  226  ls
  227  ls -a
  228  clea
  229  clear
  230  exit
  231  node -v
  232  sudo su
  233  ls
  234  cd aulas
  235  ls
  236  clear
  237  ls
  238  cat 'Comandos Kubernetes.txt' 
  239  k3d cluster create meucluster --servers 1 --agents 2 -p "8080:30000@loadbalancer"
  240  kubectl cluster-info
  241  k3d cluster list
  242  kubectl get nodes
  243  kubectl get replicaset
  244  kubectl get pods
  245  kubectl get all
  246  kubectl get nodes
  247  k3d cluster delete meucluster
  248  ls
  249  cd kubernetes/
  250  ks
  251  ls
  252  cat deploy.yaml 
  253  clear
  254  ls
  255  cat deployment.yaml 
  256  clear
  257  ls
  258  cat pod.yaml 
  259  clear
  260  cat replicaset.yaml 
  261  clear
  262  cd ..
  263  ls
  264  exit
  265  code .
  266  exit
  267  ls
  268  code .
  269  clear
  270  docker -v
  271  clear
  272  gemini
  273  clear
  274  exit
  275  docker /?
  276  docker --help
  277  docker ps
  278  docker ps -a
  279  docker
  280  docker ls
  281  docker ps
  282  docker ps -a
  283  docker ps a
  284  clear
  285  docker ps
  286  cd .kube
  287  ls
  288  cd /home/fabio/.kube/
  289  ls
  290  docker run -i -rm -v /home/fabio/.kube:/home/appuser/.kube mcp/kubernetes
  291  docker run -i -v /home/fabio/.kube:/home/appuser/.kube mcp/kubernetes
  292  sudo docker run -i -v /home/fabio/.kube:/home/appuser/.kube mcp/kubernetes
  293  docker ps
  294  sudo su
  295  docker ps
  296  exit
  297  ls -a
  298  cd .kube
  299  ks
  300  ls
  301  cd config
  302  cat config 
  303  cd /home/fabio
  304  ls
  305  clear
  306  cd .gemini
  307  ls
  308  nano settings.json 
  309  cd ..
  310  clear
  311  gemini
  312  cd .gemini
  313  nano settings.json 
  314  cd ..
  315  clear
  316  gemini
  317  cd .gemini
  318  nano settings.json 
  319  gemincd.. 
  320  cd..
  321  cd ..
  322  gemini
  323  clear
  324  gemini
  325  exit
  326  chmod +x /home/fabio/.kube
  327  sudo docker run -i -v /home/fabio/.kube:/home/appuser/.kube mcp/kubernetes
  328  k3d cluster create meucluster --servers 1 --agents 1 -p "8080:30000@loadbalancer"
  329  kubectl cluster-info
  330  kubectl get nodes
  331  sudo docker run -i -v /home/fabio/.kube:/home/appuser/.kube mcp/kubernetes
  332  chmod 644 /home/fabio/.kube/confi
  333  chmod 644 /home/fabio/.kube/config
  334  sudo docker run -i -v /home/fabio/.kube:/home/appuser/.kube mcp/kubernetes
  335  clear
  336  docker p
  337  docker ps
  338  kubetctl get pods
  339  kubectl get pods
  340  kubectl get pod
  341  k3d ls
  342  k3d 
  343  k3d list
  344  k3d cluster 
  345  k3d cluster list
  346  kubectl get nodes
  347  kubectl get all
  348  kubectl get pods
  349  kubectl get nodes
  350  docker ps
  351  kubectl get pods
  352  kubectl get nodes
  353  kubectl get services
  354  clear
  355  code .
  356  cd aulas
  357  ls
  358  cd AIOps/
  359  clear
  360  git clone https://github.com/fabricioveronez/catalogo-docker-compose/tree/main/n8n/docker-compose.yaml
  361  git clone https://github.com/fabricioveronez/catalogo-docker-compose/tree/main/n8n
  362  git clone 
  363  git clone https://github.com/fabricioveronez/catalogo-docker-compose/tree/main/n8n .
  364  git clone "https://github.com/fabricioveronez/catalogo-docker-compose/tree/main/n8n" .
  365  git clone "https://github.com/fabricioveronez/catalogo-docker-compose/n8n .
  366  exit
  367  exit
  368  git clone "https://github.com/fabricioveronez/catalogo-docker-compose/n8n
  369  git clone "https://github.com/fabricioveronez/catalogo-docker-compose/n8n" .
  370  git clone https://github.com/fabricioveronez/catalogo-docker-compose .
  371  ls
  372  cd n8n
  373  ld
  374  ls
  375  docker compose up docker-compose.yaml 
  376  docker compose docker-compose.yaml up
  377  docker compose up docker-compose.yaml
  378  docker compose up 
  379  docker ps
  380  k3d cluster 
  381  k3d cluster list
  382  k3d cluster delete meucluster
  383  k3d cluster list
  384  docker
  385  docker ps
  386  cd aula
  387  cd aulas
  388  ls
  389  cd AIOps/
  390  ls
  391  cd aulas
  392  ls
  393  cd ..
  394  cd n8n/
  395  ls
  396  docker compose down
  397  docker la 
  398  docker ls
  399  exit
  400  cd aula
  401  cd aulas
  402  ls
  403  cd terraforms
  404  md terraform
  405  mk terraform
  406  gemini
  407  make terraform
  408  mkd terraform
  409  md terraform
  410  mkdir terraform
  411  cd terraform/
  412  clear
  413  ls
  414  gemini
  415  exit
  416  cd aula
  417  cd ulas
  418  cd aulas
  419  cd terraform/
  420  ls
  421  code .
  422  aws configure 
  423  clear
  424  terraform plan
  425  terraform apply
  426  terraform destroy
  427  exit
  428  code .
  429  cd aulas/
  430  cd terraform/
  431  ls
  432  clear
  433  code .
  434  ssh-keygen -t rsa
  435  ls ~/.ssh/id_rsa.pub
  436  terraform plan
  437  terraform apply
  438  ssh -i ~/.ssh/id_rsa ubuntu@18.222.167.115
  439  ls ~/.ssh/
  440  cat ~/.ssh/id_rsa.pub 
  441  cat ~/.ssh/id_rsa
  442  clear
  443  terraform plan
  444  terraform apply
  445  terraform destroy
  446  clear
  447  terraform apply
  448  curl -I http://3.148.194.6
  449  curl -I http://3.17.148.245
  450  terraform apply
  451  echo "alias tf='terraform'" >> ~/.bashrc
  452  source ~/.bashrc
  453  clear
  454  tf plan
  455  tf apply
  456  tf plan
  457  tf apply
  458  clear
  459  tf destroy
  460  exit
  461  ls -a
  462  cd .gemini/
  463  ls
  464  cat settings.json 
  465  cp settings.json settings.json.bkp
  466  nano settings.json
  467  clear
  468  gemini -r
  469  clear
  470  cd ..
  471  cd aulas
  472  ls
  473  cd terraform/
  474  ls
  475  clear
  476  gemini -r
  477  cd aulas
  478  s
  479  ls
  480  mkdir terraform_lab
  481  cd terraform_lab/
  482  ls
  483  copy * ../terraform/ .
  484  cp * ../terraform/ .
  485  cp * ../terraform/ . -r
  486  ls
  487  cd terraform/
  488  l
  489  ls
  490  cd ..
  491  cp * ../terraform . -r
  492  ls
  493  cp ../terraform/* . -r
  494  ls
  495  cd terraform/
  496  ls
  497  rm *
  498  ls
  499  cd ..
  500  rmdir terraform/
  501  cd terraform/
  502  ls
  503  ls -a
  504  cd ..
  505  ls
  506  cd terraform/.terraform/
  507  ls
  508  cd providers/
  509  ls
  510  cd ..
  511  cd .
  512  cd ..
  513  rm -s 
  514  ls
  515  rmdir terraform/ -s
  516  rmdir --help
  517  rmdir -p terraform/
  518  rmdir -p terraform/ --ignore-fail-on-non-empty
  519  ls
  520  cd terraform/
  521  ls
  522  ls -a
  523  cd ..
  524  cd terraform
  525  clear
  526  terraform plan
  527  tf apply
  528  tf destroy
  529  clear
  530  ls
  531  cd ..
  532  cd terraform_lab/
  533  ls
  534  rmdir -rf terraform/
  535  rmdir -rf terraform
  536  rm -rf terraform
  537  ls
  538  cd la -a
  539  ls -a
  540  cd ..
  541  mkdir terraform_lab2
  542  cd terraform_lab2/
  543  cp ../terraform/*
  544  cp * -s ../terraform
  545  cp -s ../terraform
  546  cp -s ../terraform .
  547  cp -r ../terraform .
  548  ls
  549  cd terraform
  550  ls
  551  ls -a
  552  cd ..
  553  clear
  554  cd terraform
  555  ls
  556  exit
  557  cd aulas
  558  cd terraform/
  559  ls
  560  code ,
  561  code .
  562  gemini -r
  563  exit
  564  cd aula
  565  cd aulas
  566  ls
  567  mkdir terraform_lab3
  568  cd terraform_lab3
  569  ls
  570  code ,
  571  code .
  572  tf init
  573  tf plan
  574  tf apply
  575  ls
  576  labs
  577  mkdir lbs
  578  rm lbs
  579  rm -rf lbs
  580  mkdir labs
  581  ls
  582  cd labs
  583  ls
  584  clear
  585  git clone git@github.com:josefabiorosa/lab_github.git
  586  ls
  587  cd lab_github/
  588  ls
  589  cat > README.md 
  590  cat README.md 
  591  cat >> README.md 
  592  cat README.md 
  593  git status
  594  git add .
  595  git commit -m "Primeira versao do Readme.md"
  596  git status
  597  git push
  598  clear
  599  git branch fabio_01
  600  git branch
  601  git checkout fabio_01
  602  git branch
  603  ls
  604  code README.md
  605  git status
  606  git add .
  607  git commit -m 'Alteração do Arquivo feita por Branch: Fabio01'
  608  git push -u original fabio_01
  609  git push
  610  git push -u origin fabio_01
  611  cat > teste.txt
  612  ls
  613  git branch
  614  clear
  615  git add .
  616  git commit -m "Adicionado arquivo criado pela branch fabio _01"
  617  git push
  618  ls
  619  git checkout main
  620  git status
  621  ls
  622  git pull
  623  ls
  624  git branch fabio_02
  625  git checkout fabio_02
  626  git branch
  627  cls
  628  ls
  629  git checkout main
  630  clear
  631  git status
  632  ls
  633  code .
  634  ls
  635  git status
  636  clear
  637  git checkout fabio_01
  638  code .
  639  ls
  640  git pull
  641  ls
  642  code .
  643  git add .
  644  git commit -m "Add alteração no index.html feito pela branch fabio_01"
  645  git push
  646  ls
  647  git pull
  648  ls
  649  git checkout main
  650  ls
  651  cat index.html 
  652  git pull
  653  ls
  654  cat index.html 
  655  git checkout fabio_02
  656  ls
  657  git pull
  658  code .
  659  ls
  660  git checkout main
  661  ls
  662  git branch
  663  git pull
  664  ls
  665  git pull
  666  ls
  667  git checkout fabio_02
  668  git merge origin main
  669  ls
  670  git checkout fabio_01
  671  ls
  672  git checkout fabio_02
  673  ls
  674  git checkout fabio_01
  675  git merge origin fabio_02
  676  ls
  677  clear
  678  ls
  679  git status
  680  git push
  681  git status
  682  git checkout fabio_02
  683  git push
  684  git status
  685  git checkout main
  686  git status
  687  clear
  688  git pull
  689  git checkout fabio_01
  690  ls
  691  code teste.txt
  692  git add .
  693  git commit -m "Alterando o arquivo teste.txt branch fabio_01"
  694  git push
  695  git checkout fabio_02
  696  code teste.txt
  697  git add .
  698  git commit -m "Alterando o arquivo teste.txt branch fabio_01"
  699  git push
  700  clear
  701  git checkout main
  702  echo "Linha 1: Versao original" > desafio.txt
  703  git add desafio.txt
  704  git commit -m "Criando arquivo base na main"
  705  git checkout -b teste-conflito
  706  echo "Linha 1: Alterada pela branch de teste" > desafio.txt
  707  git add desafio.txt
  708  git commit -m "Alteracao na branch teste-conflito"
  709  git checkout main
  710  echo "Linha 1: Alterada pela branch main" > desafio.txt
  711  git add desafio.txt
  712  git commit -m "Alteracao na branch main para gerar conflito"
  713  git checkout teste-conflito
  714  git merge main
  715  ls
  716  code desafio.txt 
  717  git add desafio.txt
  718  git commit -m "Conflito resolvido com sucesso!"
  719  git log --graph --oneline --all
  720  clear
  721  git checkout main
  722  git push
  723  clear
  724  echo "function saudar() { console.log('Ola Mundo'); }" > funcoes.js
  725  echo "body { color: black; }" > estilo.css
  726  ls
  727  git add .
  728  git commit -m "Configuracao inicial: funcoes e estilo"
  729  git push origin main
  730  git checkout -b user1
  731  echo "body { color: blue; }" > estilo.css
  732  git add estilo.css
  733  git commit -m "User01 mudou a cor para azul"
  734  git push origin user1
  735  git checkout main
  736  git checkout -b user2
  737  # O User02 decide mudar o nome da função de 'saudar' para 'dizerOla'
  738  echo "function dizerOla() { console.log('Ola Mundo'); }" > funcoes.js
  739  git add funcoes.js
  740  git commit -m "User02 renomeou a funcao"
  741  git checkout main
  742  git pull origin main  # Agora sua main local tem o estilo azul do User01
  743  git checkout user2
  744  git merge main        # O Git vai dizer: "Merge made by the 'recursive' strategy"
  745  clear
  746  code .
  747  git checkout main
  748  code
  749  history
  750  git checkout main
  751  history > git_comandos.md
