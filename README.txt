About Time Spinner.

	Time Spinner is a time selector tool based on YUI3.



Time Spinner Config.


	var timespinner = new Y.TimeSpinner{... 

		hourtype:'12', ('hourtype' is either 12 or 24 hr format.)
		separator:':',  ('separator' the separator to be used in between hh:mm:ss.)
		seconds:true,  ('seconds' true or false as wether or not ss are required.)
		timepsan:{required:true,sep:' - '},  ('timepsan' true or false and the spearator to be used.)
		holder:'#...'  (the id of the element to where the time spinner will be drawn.)


Time Spinner Example.

Time Spinner 
12 hour clock, with seconds, with a time span.

var timespinner = new Y.TimeSpinner({
       hourtype:'12',
       separator:':',
       seconds:true,
       timepsan:{required:true,sep:' - '},
	   holder:'#boxd'
    });
    timespinner.render();
    timespinner.focus();


To get the value of the time spinner. 'timespinner.getValue();'

