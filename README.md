# dotgit
personal gitdot files  
including conditinal include in ~/prv/

---------------------------------------------------------------------

    git clone https://github.com/Slm0n87/dotgit.git ~/.git
    mv ~/.gitconfig ~/.gitconfig_backup
    ln -s ~/.git/gitconfig_prv ~/prv/.gitconfig
    ln -s ~/.git/gitconfig ~/.gitconfig
    ln -s ~/.git/gitignore ~/.gitignore
    sed -i 's/YOURNAMEHERE/John Doe/' gitconfig
    sed -i 's/YOUREMAILHERE/foo@bar/' gitconfig
    sed -i 's/YOURNAMEHERE/John Doe Prv/' gitconfig_prv
    sed -i 's/YOUREMAILHERE/foo@barprv/' gitconfig_prv

install git:
---------------------------------------------------------------------

    apt install git


known issues::
---------------------------------------------------------------------

-    
