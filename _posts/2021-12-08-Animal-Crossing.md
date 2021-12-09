## How I Used the API
As we learned in class, to receive data/information from an API, I needed a few pieces of information such as the BASE_URL, payload, ENDPOINT, and API_KEY. The received data can be converted into text to be written into a CSV file. Constant requests were made to the API, which provided me with the sock objects needed. The data objects were received with the get() method defined within the function. The data (sock) objects (once converted to a text format which was a readable format) were then written into the CSV file created with the CSV() method. 

## List of Socks with the Most Variations
['argyle crew socks', 'color-blocked socks', 'frilly knee-high socks', 'holey tights', 'kiddie socks', 'mixed-tweed socks', 'no-show socks', 'semi-opaque socks', 'semi-opaque tights', 'sequin leggings', 'simple-accent socks', 'striped socks', 'striped tights', 'tube socks', 'ultra no-show socks', 'vivid leggings', 'vivid socks', 'vivid tights']

## Socks of Each Color
{'Pink': 41, 'Red': 39, 'Green': 50, 'Light blue': 33, 'Orange': 27, 'Purple': 37, 'Blue': 47, 'Yellow': 33, 'Beige': 15, 'White': 85, 'Black': 59, 'Brown': 11, 'Gray': 31, 'Colorful': 14}

## My Process
In my process of working on this lab, I worked closely with Jack, Justin, and Mikhail. 

In my approach to the lab I first worked on the creation of the CSV() method, which would also compel me to work on API requests. I began with thinking that I could directly apply the template code provided by the Pokemon API practice from class. This aforementioned approach did not work and I had trouble applying the concept of making multiple requests. After working with Jack, I was able to help translate my vague idea of the pseudocode needed into hard code for the CSV() method. Continuing off of the construction of the CSV() method, I was able to work with things such as counting for duplicates and creating a list of sock types with maximum variation values. 

Coming into this lab, I still had trouble with hard coding excerpts of making requests to APIs and receiving data from them. As a result, I sought to solidify my skills centered around making requests to APIs and receiving data objects from them. Throughout the lab I learned about making repeated requests to the API and converting the data objects I receive into readable formats that can be written into a newly created CSV file. Having to create a new CSV file rather than being given one posed a unique challenge, and it helped me solidify my skills regarding APIs and data object conversion. Finally, I found it most interesting when I took on the challenge of learning about counting for duplicates, which I had learned with Mikhail. 
