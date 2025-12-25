Search parse passwords leaks.

LeakSearch is a simple tool to search and parse plain text passwords using ProxyNova COMB (Combination Of Many Breaches) over the Internet. You can define a custom proxy and you can also use your own password file, to search using different keywords: such as user, domain or password.

you can also export txt & json files.


 Functions: 
-hdisplays on-screen help
-dThis will allow us to select the database (default, ProxyNova)
-kto search by keyword (username, domain, or password)
-nIt will show us the number of results we specify.
-eitherThis will allow us to save the results in JSON or TXT format.
-pto use an HTTP/S proxy

Now that we know how it works, let's put it into practice with the following command:

python3 LeakerCheck.py -k password -n 10

python3 LeakerCheck.py -k com -n 10 -d 

python3 LeakerCheck.py -h

Installation:

git clone https://github.com/0xvileness/LeakChecker.git
cd LeakChecker
pip3 install -r requirements.txt
python3 LeakCheck.py 
