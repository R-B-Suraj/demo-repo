# Demo
header is given using #
some description...
there is commit changes message below which is used to tell something about changes made

## sub header
a sub header is given using ##
type ls -la to see hidden files also...

create a new file index.html
we can check status by         git status
also in folder section we can see M for modified and U  for untracked 
untracked means git doesn't know about the file yet...
we have to tell git to track the file before save it
people use .     means to track all the files  git add .
we can also tell the individual files... git add index.html


while commiting we need to add message which says why what are the changes

git commit -m "commit message title" -m "some description"

we still haven't pushed it live to github ( remote ripository on which it is hosted)..  it is just saved in local






..........  we need to push it.......
for that git has to know that we are the owner of the repository
done by creating ssh key....


ssh-keygen -t rsa -b 4096 -C "rb.suraj1kanha@gmail.com"
... t  type      b  strength of encryption    git hub email address

follow on..
search keys

isa.pub  is public....  ok for other people to see this

isa      is private....  must not share.... (local system access)
private key shows that this is the system that generated that public key


how to copy in github bash... command line
because ctrl+c   has different meaning...  exit ungoing process
just select  and it gets copied automatically





adding your ssh key to ssh agent
making sure that local git CLI know about the key i just generated

https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_rsa




git push origin master

origin is option set for us .. basically a word that stands for location of our git ripository



............... ALL THE ABOVE  ARE FOR THE CASE WHERE WE  modified  repository  using github ...

what about starting a project locally


