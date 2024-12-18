# bikes-in-bikewale
import requests
from bs4 import BeautifulSoup
import csv

url="https://www.bikewale.com/royalenfield-bikes/"
page=requests.get(url)

soup=BeautifulSoup(page.content,'html.parser')
print(soup.text)






