# Codeigniter mongodb driver

Codeigniter 3.x Mongodb 3.x Driver (Php5 / Php7)
## Setting
<ol>
<li>Copy Mdb.php file into application/libraries directory.</li>
<li>Add Mdb.php to&nbsp;$autoload['libraries'] = array(); (application/config/autoload.php)</li>
</ol>
## Usage:
<p>

$this->mdb->insert('collection',$data=array());
$last_id = $this->mdb->insert_id();

</p>
<p>&nbsp;</p>
