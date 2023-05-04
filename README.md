# ![Tagh Time Front App]


# Getting started with Front-end in linux server
## Dependencies
     node -v = 19.* 
     npm -v 9.6.*
     
----------     
## Installation

Clone the repository

    git clone git@gitlab.com:amidigital/tagh-time-fe.git

Switch to the repo folder

    cd tagh-time-fe


Switch to the main branch

    git checkout main
    
Install all the dependencies using npm

    npm i --quite


Copy the example env file and make the required configuration changes in the .env file


    cp .env.example .env

----------

## Configuration .env file
Copy the example env file and make the required configuration changes in the .env file


    cp .env.example .env

change  following values

| **Key**                                        | **Value**                                                      |
|------------------	                             |--------------------------------------------------	            |
| VITE_IS_LIVE_SERVER       	                   | true                                                           |
| VITE_BASE_BACKEND_URL_DOMAIN 	                 | your backend server domin URL e.g :taghtime.com	              |
| VITE_BASE_REGISTER_BACKEND_URL_DOMAIN    	     | your domin URL without http schema e.g   : back.taghtime.com  	|


## Build App

     quasar build


You can now access the server at http://localhost:9000/
