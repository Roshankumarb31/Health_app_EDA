<body>
<h1>Data Analytics for Loghub Healthapp Dataset</h1>

<h2>Dataset</h2>
<p>HealthApp is a mobile application for Andriod devices. The application logs from an Android smartphone after 10+ days of use were collected.

<code>git clone https://github.com/logpai/loghub/blob/master/HealthApp</code>

Basic Data Analytics have been done for this dataset.
</p>


<h2>Inferences</h2>

<h3>Description</h3>
<p>The desciption of the dataset is infered using pandas <code>df.describe()</code> method and the following inferences were made:
</p>


<img src="https://ik.imagekit.io/tejasram/screenshots/describe_graphs.png?updatedAt=1694245012665" alt="Dataset description graphs" width="350"></img>

<h3>Inferences based on Time</h3>
<p>The 'Time' column was structured into 'Date' and 'Time' columns using the pandas <code>to_datetime()</code> method. The following inferences can be made:</p>
<img src="https://ik.imagekit.io/tejasram/screenshots/time_steps.png?updatedAt=1694245012759" alt="Time based inferences" width="700"></img>
<p>From this, we can infer the time when the person is most active and when the person is inactive.</p>

<h3>Frequency of 'Contents' in the dataset</h3>
<p>The dataset's attributes were grouped using the pandas <code>groupby()</code> method to the total unique contents present in the dataset. The following was the infered Frequencies of the Content column:</p>
<img src="https://ik.imagekit.io/tejasram/screenshots/component_frequency.png?updatedAt=1694245015258" alt="Frequencies Graph for Contents" width="700"></img>

<h3>Frequency of 'Components' in the dataset</h3>
<p>Similarly, the attributes were grouped to the unique 'Components' present in the dataset. The inference of the Frequencies in which different components occure can be made:  </p>
<img src="https://ik.imagekit.io/tejasram/screenshots/content_frequency.png?updatedAt=1694245013096" alt="Components Graph for Contents" width="700"></img>

<h3>Events for each component</h3>
<p>The count of events is taken after grouping the components together. This would allow us to infer the number of events which are on a particular component. The inference can be observed as follows:</p>
<img src="https://ik.imagekit.io/tejasram/screenshots/event_count.png?updatedAt=1694245020181" alt="Event count for components" width="700">


</body>
