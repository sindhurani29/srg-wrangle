# srg-wrangle
2. My assigned play is **The Comedy of errors**
3. My speaker 1 is Sindhuja Valeti.
4. My speaker 2 is Mohan Krishna Alavala.
5. Question is 'How to redirect the output to result.txt
6. Commands used are
**Curl command:**  curl "http://shakespeare.mit.edu/comedy_errors/full.html" -O srg.txt 
**redirect output to result.txt:**  tr ' ' '\12' < srg.txt | sort | uniq -c | sort -nr > result.txt
