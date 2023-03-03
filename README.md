# Description
A thin python wrapper for pivpn

# Installation
pip3 install pivpnpy

# Usage
```python3
from pivpnpy import pivpn

# Create a user
pivpn.create_profile(user="Hello_World", ttl=1080)

# List users
profiles = pivpn.list_profiles()
print(profiles[0]['status'])  # Prints "Valid"

# Delete a user
pivpn.delete_profile(user="Hello_World") 
```