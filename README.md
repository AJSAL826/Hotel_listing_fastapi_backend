# Hotel_listing_fastapi_backend

## Features

A User can create new hotels with details.

A user can search the hotel details based on his preference and filterations.

## Fields

name :str

occupancy :int

bathroom_count :int

city :str

state :str

country :str

pin :Union[str,int]

contact_number :Union[int,str]

rate_per_day :Optional[Union[float,int]]

A User can retrieve the details of all hotels based on his preference . 

### Mandatory Field for Search

User must enter either the name or city of the hotels for searching.
