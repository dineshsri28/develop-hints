<h4 id="hours">To Find how many hour</h4>
<p>This code give answer like (50 minutes ago)</p>

     const timestamp = moment(dateFromDatabase, 'ddd MMM DD YYYY HH:mm:ss GMT Z').diff(Date.now(), 'hours');

<h4>Disable Date</h4>
<p>For date picker to disable previous date</p>

    const todisabledDate = (value) => {
    let yes = moment().subtract(1, "days");
    return value < yes;
    };

<h4>Truncate Text</h4>
<p>This css make the text as (...) if content overflow from the parent container

    p {
    width: 200px;
    white-space: nowrap;
    overflow: hidden;
    display: inline-block;
    text-overflow: ellipsis;
    border: 1px solid #ddd;
    margin: 0;
    }


<!--stackedit_data:
eyJoaXN0b3J5IjpbMTk1MTMxNzE2NywtMTkzNDg3MTY2LDkxMT
gyNDAxOV19
-->