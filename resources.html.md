---
title: KLA for Pivotal Cloud Foundry
---

# Resource requirements for KLA for Pivotal Cloud Foundry
These are the default resource and IP requirements for installing the tile:
<table border="1" class="nice">
	<tr>
		<th>Component</th>
		<th>Job</th>
		<th>Instances</th>
		<th>CPU</th>
		<th>Ram</th>
		<th>Ephemeral</th>
		<th>Persistent</th>
		<th>Static IP</th>
		<th>Dynamic IP</th>
	</tr>
	<tr>
 		<td>Zookeeper 1</td>
	 	<td>One of 5 Zookeeper Jobs</td>
	 	<td>1</td>
	 	<td>2</td>
	 	<td>2048</td>
	 	<td>8000</td>
	 	<td>2000</td>
	 	<td>1</td>
	 	<td>0</td>
 	</tr>
	<tr>
 		<td>Zookeeper 2</td>
	 	<td>One of 5 Zookeeper Jobs</td>
	 	<td>1</td>
	 	<td>2</td>
	 	<td>2048</td>
	 	<td>8000</td>
	 	<td>2000</td>
	 	<td>1</td>
	 	<td>0</td>
 	</tr>
	<tr>
 		<td>Zookeeper 3</td>
	 	<td>One of 5 Zookeeper Jobs</td>
	 	<td>1</td>
	 	<td>2</td>
	 	<td>2048</td>
	 	<td>8000</td>
	 	<td>2000</td>
	 	<td>1</td>
	 	<td>0</td>
 	</tr>
	<tr>
 		<td>Zookeeper 4</td>
	 	<td>One of 5 Zookeeper Jobs</td>
	 	<td>1</td>
	 	<td>2</td>
	 	<td>2048</td>
	 	<td>8000</td>
	 	<td>2000</td>
	 	<td>1</td>
	 	<td>0</td>
 	</tr>
	<tr>
 		<td>Zookeeper 5</td>
	 	<td>One of 5 Zookeeper Jobs</td>
	 	<td>1</td>
	 	<td>2</td>
	 	<td>2048</td>
	 	<td>8000</td>
	 	<td>2000</td>
	 	<td>1</td>
	 	<td>0</td>
 	</tr>
	<tr>
 		<td>Solr Server</td>
	 	<td>One of many Solr Server jobs</td>
	 	<td>2</td>
	 	<td>2</td>
	 	<td>8192</td>
	 	<td>30000</td>
	 	<td>100000</td>
	 	<td>1</td>
	 	<td>0</td>
 	</tr>
	<tr>
 		<td>Logstash Server</td>
	 	<td>Logstash job</td>
	 	<td>2</td>
	 	<td>2</td>
	 	<td>4096</td>
	 	<td>30000</td>
	 	<td>10000</td>
	 	<td>1</td>
	 	<td>0</td>
 	</tr>
</table>
