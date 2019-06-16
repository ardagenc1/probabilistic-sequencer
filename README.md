# probabilistic-sequencer
<html><head>
	<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
	<title> Probabilistic Sequencer by Agency666 </title>

</head>



<body>

<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.0/css/bootstrap.min.css" integrity="sha384-9gVQ4dYFwwWSjIDZnLEWnxCjeSWFphJiwGPXr1jddIhOegiu1FwO5qRGvFXOdJZ4" crossorigin="anonymous">



<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.0/jquery.min.js"></script>
<script src="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>


<div class="container"> 
<h1 class="display-4"> Probabilistic Sequencer by Agency666 </h1>
<hr class="my-4">

<h6> Arda Genc • emregenc2019@u.northwestern.edu • EECS 397: Digital Musical Instrument Design • Northwestern University • Prof. Stephan Moore </h6>



<div class="accordion" id="accordion">
  <div class="card">
    <div class="card-header" id="headingOne">
      <h5 class="mb-0">
        <button class="btn btn-link" type="button" data-toggle="" data-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
          Using the instrument
        </button>
      </h5>
    </div>

    <div id="collapseOne" class="collapse show" aria-labelledby="headingOne" data-parent="#accordion">
      <div class="card-body">
        <strong>Expected user: </strong> The ideal user is an underground techno DJ/Producer who values improvisation during live performances. 
 <br> <br>

		<strong> Expected use case:</strong> DJ Set/Live performance. The performer would ideally have other hardware and software in use. Probabilistic Sequencer would support the performer in creating melodies through improvisation with the hardware and adding an element of unpredictability through the controllable probabilities.  <br> <br>

		<strong> How is the instrument played? What kinds of sounds are produced? </strong> The instrument is played by choosing the note to modify, changing the note value and probability, and turning notes on and off. Knobs allow the user to browse through notes and choose the desired note and probability. Buttons serve to turn the notes on and off as well as control the drum machine. The sounds played are imported from Ableton sound library and can be modified. Ideally, one sequencer controls a synth sound and the other one controls a drum kit.
      </div>
    </div>
  </div>
  <div class="card">
    <div class="card-header" id="headingTwo">
      <h5 class="mb-0">
        <button class="btn btn-link" type="button" data-toggle="" data-target="#collapseTwo" aria-expanded="true" aria-controls="collapseTwo">
          Building the instrument
        </button>
      </h5>
    </div>
    <div id="collapseTwo" class="collapse show" aria-labelledby="headingTwo" data-parent="#accordion">
      <div class="card-body">
        <strong> How is it built? What software and hardware are used? </strong> The 16-step probabilistic sequencer is built using a MAX/MSP patch. The sounds played are from Ableton sound library. Hardware to control the sequencer is built using an Arduino Uno, a breadboard, 3 potentiometers, 2 buttons, and an LED. The sensor values are sent from the Arduino to the serial port, and from the serial port to the Max Patch, where the parameters are modified and sound is outputted. 
      </div>
    </div>
  </div>
  <div class="card">
    <div class="card-header" id="headingThree">
      <h5 class="mb-0">
        <button class="btn btn-link" type="button" data-toggle="" data-target="#collapseThree" aria-expanded="true" aria-controls="collapseThree">
          Lessons Learned
        </button>
      </h5>
    </div>
    <div id="collapseThree" class="collapse show" aria-labelledby="headingThree" data-parent="#accordion">
      <div class="card-body">
        <strong> What lessons did I learn from making this instrument?  </strong> The best way to learn is by doing. No matter how much I planned beforehand, I got the most useful feedback once I had an iteration of my instrument built and started using it. It was hard to predict what way of doing certain things would be easiest to use. For example, I thought that browsing through the notes would be a good solution, but it ended up breaking my flow while using the instrument. Therefore, I learned that in this kind of large, multi-component projects, it is best to start by building low fidelity versions and build up to the final product step by step. I also realized that, as the hardware and code became more complex, it became significantly harder to debug my work. Therefore, it is important to write comments and document one’s work well to make future modifications more manageable. <br> <br>

        <strong> What might I improve on in future iterations?  </strong> I envision multiple future iterations before I can build the final version of this instrument. On the next iteration, I will make the controls complete, as I still have to control some of the parameters using the max interface from the laptop. Specifically, I will add a note length control, implement granular note value and probability control for the drum machine, and make a re-sync button. <br> <br>

        Since I noticed that it’s not very convenient to have two knobs to control the note value and probability of all 16 notes, in the next version, I will give each note a dedicated note value and probability knob, and limit browsing to switching between melody controls and drum controls. This will give the user much more flexibility <br> <br>

        Finally, for the final iteration, I will make a clean user interface that is easier to use. This will include cleaning up the Max Patch and creating a more visual Presentation Mode, 3-D printing the hardware parts to have a higher quality feel, and implementing LEDs and screens to give the user feedback on the current status of the notes and probabilities. For instance, a set of 16 LEDs of various colors that represent each note at the sequencer and light up when the note is playing would be a great visual addition, as suggested by Professor Moore.
      </div>
    </div>
  </div>
  <div class="card">
    <div class="card-header" id="headingFour">
      <h5 class="mb-0">
        <button class="btn btn-link" type="button" data-toggle="" data-target="#collapseFour" aria-expanded="true" aria-controls="collapseFour">
          Pictures
        </button>
      </h5>
    </div>
    <div id="collapseFour" class="collapse show" aria-labelledby="headingFour" data-parent="#accordion">
      <div class="card-body">
         <div class="container">
		  <div class="row">
		    <div class="col-sm">
		      <figure class="figure">
		      	<img src="https://www.dropbox.com/s/elit1xumfh1ekpw/333.jpeg?raw=1" class="figure-img img-fluid" alt="A generic square placeholder image with rounded corners in a figure.">
		  		<figcaption class="figure-caption">Performer's view of the instrument. In the future iterations, LEDs and screen displays will be implemented for better feedback. Hardware parts will be 3-D printed for high quality feel. </figcaption>
		  	  </figure>
		    </div>
		    <div class="col-sm">
		      <figure class="figure">
		      	<img src="https://www.dropbox.com/s/lnn077ojigrzdjz/222.jpeg?raw=1" class="figure-img img-fluid" alt="A generic square placeholder image with rounded corners in a figure.">
		  		<figcaption class="figure-caption">Side view of the instrument. Browse knob allows the user to browse through the steps to choose the note that is being modified.</figcaption>
		  	  </figure>
		    </div>
		    <div class="col-sm">
		      <figure class="figure">
		      	<img src="https://www.dropbox.com/s/gah7ysbs86bbmgl/444.jpeg?raw=1" class="figure-img img-fluid" alt="A generic square placeholder image with rounded corners in a figure.">
		  		<figcaption class="figure-caption">Top view of the instrument. After choosing the note to modify out of the 16 steps, the user can modify the note value and probability using the knobs, as well as turn the note on and off using the button. </figcaption>
		  	  </figure>
		    </div>
		</div>
      </div>
    </div>
  </div>
  <div class="card">
    <div class="card-header" id="headingFour">
      <h5 class="mb-0">
        <button class="btn btn-link" type="button" data-toggle="" data-target="#collapseFour" aria-expanded="true" aria-controls="collapseFour">
         Video Demo
        </button>
      </h5>
    </div>
    <div id="collapseFour" class="collapse show" aria-labelledby="headingFour" data-parent="#accordion">
      <div class="card-body">
           <iframe width="853" height="480" src="https://www.youtube.com/embed/Dswi1M9LFOc" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen=""></iframe>
      </div>
    </div>
  </div>


</div>





</div></body></html>
