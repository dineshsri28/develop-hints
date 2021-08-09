<h4 id="hours">To Find how many hour</h4>
<p>This code give answer like (50 minutes ago)</p>

     const timestamp = moment(dateFromDatabase, 'ddd MMM DD YYYY HH:mm:ss GMT Z').diff(Date.now(), 'hours');

<h4>Disable Date</h4>
<p>For date picker to disable previous date</p>

    const todisabledDate = (value) => {let yes = moment().subtract(1, "days");return value < yes;};


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE5MzQ4NzE2Niw5MTE4MjQwMTldfQ==
-->