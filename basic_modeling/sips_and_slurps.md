# SIPS and SLURPS

SIPs and SLURPs are the two key elements to the [SIPmath Standard](http://probabilitymanagement.org/standards.html), a
standard designed for the communication of uncertain quantities.

A SIP, or _Stochastic Information Packet_, contains a name field, describing the quantity being measured, a provenance
field, detailing the source of the data, and a list of the samples representative of the quantity being measured.

A SLURP, or _Stochastic Library Unit with Relationships Preserved,_ is a collection of potentially related SIPs, with
relationships preserved via the order of the samples within each SIP.

The SIPmath Standard is managed by [Probability Management](http://probabilitymanagement.org/what-we-do.html), a
non-profit which helps businesses manage their uncertainty.  

Guesstimate currently can import JSON Slurps via the 'file' menu within a space. Each SIP within the SLURP will be
imported as a new metric at the bottom of the model, with the name, reasoning, and data of the metric inferred from the
SIP.

The SIPmath standard allows for SLURPs to come in many formats, but Guesstimate can only currently import the JSON
format. An Example JSON SLURP is shown below.

<pre>{
  "name": "exampleSLURP",
  "count": "2",
  "coherent": "true",
  "provenance": "example SLURP provenance",
  "sips": [
    {
      "name": "Domestic",
      "count": "10",
      "type": "CSV",
      "csvr": "1",
      "ver": "1.0.0",
      "provenance": "Data from XYZ Co.",
      "average": "4.2",
      "median": "4.5",
      "value": [3.5,7.4,4.4,4.6,0.7,4.3,4.8,4.7,4.7,2.9]
    },
    {
      "name": "Foreign",
      "count": "10",
      "type": "CSV",
      "csvr": "1",
      "ver": "1.0.0",
      "provenance": "Data from XYZ Co.",
      "average": "5.0",
      "median": "4.9",
      "value": [6.2,1.1,4.8,5.0,6.0,7.8,7.0,4.5,4.6,3.0]
    }
  ]
}
</pre>
