# Bandwidth Reservation with Queues
<p>
<h5>This project aims to simulate queues in switches and show the benefit of bandwidth reservation for different classes of applications that use the network of such switches as compared to switches without queues. </h5>
<p>
<h4>Here's a little information about each of the files you see in the repository. </h4>
<p>
<h6>Congestion Creator -> This .py File is a python script to create a network of hosts and switches and pass a great deal traffic, to show the negative effects of congestion on throughput. </h6>
<p>
<h6>Congestion Creator with Queues-> This .py File is a python script to create a network of hosts and switches and shows the benefit of using queues to ensure a high level of performance despite high congestion. </h6>
<p>
<h6>Graph Creator -> Using the matplotlib and pandas python data visualization libraries, we can generate a graphical depiction of the fall in throughput, with an increase in UDP congestion and the difference with the use of queues.</h6>
<p>
<h6>Sample Output  -> This file shows some example output written into the file,sampleoutput.txt, by the congestioncreatorwithoutqueues.py file. It was generated by a real run of the project. </h6>

<h6>Sample Output with Queues -> This file shows some example output written into the file,sampleoutputwithqueues.txt, by the congestioncreatorwithqueues.py file. It was generated by a real run of the project. </h6>

If you would like to know more, read my paper on the project, or contact me about anything, feel free to shoot me an email at karthikv@onlab.us or krvegesna@gmail.com
