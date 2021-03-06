# Contributing
1) Strictly follow the Directory Structure

- `index.js` - Javascript file for the Home page
- `style.css` - Stylesheet for Home Page
- For each new experiement, create a new folder in root, javascripts folder and stylesheets folder, as shown in tree diagram.
```
├── expirement_name
│   ├── index.html
├── images
│   ├── dummy.jpg
├── index.html
├── javascripts
│   ├── experiment_name
│   │   └── experiment_name.js
│   └── index.js
├── stylesheets
│   ├── experiment_name
│   │   └── experiment_name.css
│   └── style.css
└── team.html
```

2) APIs

- System Calls

<table>
    <tr>  
      <th>Process</th>
      <th>API</th>
    </tr>
    <tr>  
        <td>Create</td>
        <td>/system_calls/create</td>
    </tr>
</table>

- CPU Scheduling
<table>
    <tr>  
      <th>Process</th>
      <th>API</th>
    </tr>
  <tr>  
    <td>FCFS</td>
    <td>/cpu_scheduling/fcfs</td>
  </tr>
  <tr>  
    <td>SJF NonPremptive</td>
    <td>/cpu_scheduling/sjf-nonpremptive</td>
  </tr>
  <tr>  
    <td>SJF Premptive</td>
    <td>/cpu_scheduling/sjf-preemptive</td>
  </tr>
  <tr>  
    <td>Priority Non-premptive</td>
    <td>/cpu_scheduling/priority-nonpreemptive</td>
  </tr>
  <tr>  
    <td>Priority Premptive</td>
    <td>/cpu_scheduling/priority-preemptive</td>
  </tr>
  <tr>  
    <td>Priority Aging</td>
    <td>/cpu_scheduling/priority-aging</td>
  </tr>
  <tr>  
    <td>Round Robin</td>
    <td>/cpu_scheduling/round_robin</td>
  </tr>
</table>


- Disk Scheduling
<table>
    <tr>  
      <th>Algorithm</th>
      <th>API</th>
    </tr>
  <tr>  
    <td>FCFS</td>
    <td>/disk_scheduling/fcfs</td>
  </tr>
  <tr>  
    <td>Shortest Seek Time First</td>
    <td>/disk_scheduling/sstf</td>
  </tr>
  <tr>  
    <td>Scan</td>
    <td>/disk_scheduling/scan</td>
  </tr>
  <tr>  
    <td>C-Scan</td>
    <td>/disk_scheduling/c_scan</td>
  </tr>
</table>
