# Data Tables

Data Tables style Bootstrap 3: <a href="https://datatables.net/examples/styling/bootstrap.html">https://datatables.net/examples/styling/bootstrap.html</a>

Pseudocode:
1. Meletakkan CDN javascript diantara tag head HTML

[code]
<head>
	//code.jquery.com/jquery-1.12.4.js
	https://cdn.datatables.net/1.10.15/js/jquery.dataTables.min.js
	https://cdn.datatables.net/1.10.15/js/dataTables.bootstrap.min.js
</head>
[/code]

2. Membuat function JavsScript di atas tag penutup body

[code]

	<script type="text/javascript">
		$(document).ready(function() {
		    $('#example').DataTable();
		} );
	</script>
	
[/code]

3. Meletakkan CDN CSS di antara tag head

[code]

	<head>
		<link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
		<link rel="stylesheet" href="https://cdn.datatables.net/1.10.15/css/dataTables.bootstrap.min.css">
	</head>

[/code]

4. Meletakkan script HTML data Table di dalam tag body

[code]

	<body>

		<table id="example" class="table table-striped table-bordered" cellspacing="0" width="100%">
	        <thead>
	            <tr>
	                <th>Name</th>
	                <th>Position</th>
	                <th>Office</th>
	                <th>Age</th>
	                <th>Start date</th>
	                <th>Salary</th>
	            </tr>
	        </thead>
	        <tfoot>
	            <tr>
	                <th>Name</th>
	                <th>Position</th>
	                <th>Office</th>
	                <th>Age</th>
	                <th>Start date</th>
	                <th>Salary</th>
	            </tr>
	        </tfoot>
	        <tbody>
	            <tr>
	                <td>Tiger Nixon</td>
	                <td>System Architect</td>
	                <td>Edinburgh</td>
	                <td>61</td>
	                <td>2011/04/25</td>
	                <td>$320,800</td>
	            </tr>
	            <tr>
	                <td>Garrett Winters</td>
	                <td>Accountant</td>
	                <td>Tokyo</td>
	                <td>63</td>
	                <td>2011/07/25</td>
	                <td>$170,750</td>
	            </tr>
	            <tr>
	                <td>Ashton Cox</td>
	                <td>Junior Technical Author</td>
	                <td>San Francisco</td>
	                <td>66</td>
	                <td>2009/01/12</td>
	                <td>$86,000</td>
	            </tr>
	            <tr>
	                <td>Cedric Kelly</td>
	                <td>Senior Javascript Developer</td>
	                <td>Edinburgh</td>
	                <td>22</td>
	                <td>2012/03/29</td>
	                <td>$433,060</td>
	            </tr>
	            <tr>
	                <td>Airi Satou</td>
	                <td>Accountant</td>
	                <td>Tokyo</td>
	                <td>33</td>
	                <td>2008/11/28</td>
	                <td>$162,700</td>
	            </tr>
	            <tr>
	                <td>Brielle Williamson</td>
	                <td>Integration Specialist</td>
	                <td>New York</td>
	                <td>61</td>
	                <td>2012/12/02</td>
	                <td>$372,000</td>
	            </tr>
	        </tbody>
    	</table>
		
	</body>

[/code]
