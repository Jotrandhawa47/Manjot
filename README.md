import requests

def get_user_info(mhkbajwa2):
    url = f"https://www.instagram.com/{mhkbajwa2}/?__a=1"
    response = requests.get(url)
    data = response.json()
    return data

username = "mhkbajwa2"
user_info = get_user_info(mhkbajwa2)
print(mhkbajwa2)
