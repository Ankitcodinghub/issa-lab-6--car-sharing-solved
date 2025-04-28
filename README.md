# issa-lab-6--car-sharing-solved
**TO GET THIS SOLUTION VISIT:** [ISSA Lab 6- Car-Sharing Solved](https://www.ankitcodinghub.com/product/issa-laboratory-6-car-sharing-1-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119118&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ISSA Lab 6- Car-Sharing Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
&nbsp;

Introduction

The topic we want to discuss today is Telematics.

Telecommuncation Informatics is the technology of sending, receiving and storing information via telecommunication devices in conjunction with affecting control on remote objects

At a very high level telematic systems comprise:

• A processing unit connected to the local system’s control interface – serial port(s), data bus(es)

• A communication device (usually a cellular network device)

• A remote command and control center

Telematic systems have a large domain of applicability – automotive, utility distribution (gas/electric), road safety, intelligent transportation, military, etc. In Continental we implement Telematics solutions particularly designed for the automotive domain. Telematics Control Units enable cars to be connected to the outside world. Common applications offered through telematics systems are:

• Door locking/unlocking and stolen vehicle tracking

• Remote diagnostics to enable early detection of failures

The application we will implement today will be focused on another application made possible by telematics: carsharing.

Before we continue, please watch this video for a brief introduction : https://www.youtube.com/watch?v=Q8EvQrKwjxY

Carsharing refers to automobile rental services intended to substitute for private vehicle ownership. Their vehicles are generally located in residential areas, priced by the hour, with convenient (generally automated) pick-up and drop-off procedures. This makes occasional use of an automobile affordable, even for low-income households, and by allowing households to reduce their vehicle ownership it provides an incentive to reduce driving and rely more on alternative modes. Carsharing services are typically developed by private companies, cooperatives or by software applications that facilitate peer-to-peer carsharing.

We are particularry interested in peer-to-peer carsharing. This model allows the user to rent a vehicle in a fully automated way by use of his smartphone, without the involvement of private companies. The process usually involves a mobile application which provides a communication environment for car owners and people who want to rent a car.

With the integration of Telematics modules in modern cars, there is no need for the client to meet the owner of the car because unlocking and starting the car can be done with the use of the mobile phone.

Preconditions

Software to install:

Python : https://www.python.org/downloads/windows/ ( please select Latest Python 3 Release)

Pycharm: https://www.jetbrains.com/pycharm/download/#section=windows

Already available items:

a) a script called carsharingClient.py which implements a TCP client

b) a script called carsharingServer.py which implements a TCP server

c) a json file cars.json containing list of authorized cars

Hints

In order to run client/server, you can run the following command.

py carsharingClient.py 127.0.0.1 -p 65432

py carsharingServer.py 127.0.0.1 -p 65432

Address and port are specified as command line parameters. If both scrips are run successfully you should be able to see two windows as shown in the image below.

Figure 1: Client &amp; Server – graphical view

Both the client and the server have the following elements:

• text box: all messages server/client are printed

• input box: collects user input

Figure 2: Input box (highlighted with yellow) → For commands entered by user

• buttons:

connect (client only): client connects to the server start (server only): server starts listening for tcp connection send: attempts sending the data from input box to server/client clear: clears text box (messages shown)

exit: exit application

Steps to connect client to server:

1. Server -&gt; Start

2. Client -&gt; Connect

You should see the red button turning green.

Figure 3: Client &amp; Server – successful connection

At startup, the server is parsing the file clients.json and saves data into class member info:

{ “authorized”: [“IS21KSM” , “BT78TMM”, “SV20ROI”, “NT03ERM”, “VS45ATP”, “BC73KLB”] }

Please be aware of:

1. Received messages are colored with blue (in client / server).

Figure 4: Client sending request to start rental to server

2. Notifications are colored with a black background.

Figure 5: Notifications – Display

Tasks

Exercise 1

Please fill in the necessary code in method parse_json from class Server.

The authorized car_ids (from the json file) must be added to list self.auth_clients.

Exercise 2

The client shall request “start-rental &lt;car_id&gt;” to server.

The server will check if &lt;car_id&gt; is authorized for rental. This will be done by checking whether the &lt;car_id&gt; is in self.auth_clients.

If it is, then server adds &lt;car_id&gt; to self. rentals_in_progress and sends “authorized” to client.

If it isn’t, then server sends “not-authorized” to client.

Note: You must only modify method handle_message from class Server:

if command.startswith(‘start-rental’):

print_system_notification(‘start-rental’)

Exercise 3

The client shall request “end-rental &lt;car_id&gt;” to server.

The server shall check if the car was rented. This will be done by checking whether the &lt;car_id&gt; is in self. rentals_in_progress.

If yes, then it will respond with “end-rental success”.

If not, then it will respond with “end-rental error not-found”.

Note: You must only modify method handle_message from class Server:

if command.startswith(‘end-rental’):

print_system_notification(‘end-rental’)

Evaluation

Score:

a) 2 point(s)

b) 2 point(s)

c) 2 point(s)
