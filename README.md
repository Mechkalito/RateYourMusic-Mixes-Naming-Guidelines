<h1>RateYourMusic: Naming Guidelines for Mixes</h1>

This is a nomenclature proposal for [RateYourMusic](https://rateyourmusic.com)'s (RYM) category which encompasses DJ mixes and live electronics. 

The problems that this project addresses are:
<ul>
	<li>Current RYM framework is unable to accommodate recordings described below, since it was created in the pre-internet era, and is oriented around physical releases.</li>
	<li>These releases are frequently deleted and just temporarily hosted.</li>
</ul>

Main goals are **information preservation** and **conciseness** when it comes to information presented to the users. This means that information supported by the website's framework, should be omitted from the title and entered in the corresponding fields, like artist's name, release date, and recording date. 

<h2>Taxonomy of Mixes</h2>

<table>
	<tr>
		<th colspan="4" rowspan="5"></th>
		<th colspan="5">Hosted By?</th>
	</tr>
	<tr>
		<th rowspan="3">Artist / Platform / Label</th>
		<th colspan="4">Named Hosts</th>
	</tr>
	<tr>
		<th rowspan="2">Podcast / Mix Series</th>
		<th colspan="3">Radio</th>
	</tr>
	<tr>
		<th>Radio Guest Mix</th>
		<th>Radio Show Mix</th>
		<th>Radio Residency Mix</th>
	</tr>
	<tr>
		<th><a href="#a">A</a></th>
		<th><a href="#b">B</a></th>
		<th><a href="#c">C</a></th>
		<th><a href="#d">D</a></th>
		<th><a href="#e">E</a></th>
	</tr>
	<tr align="center">
		<th rowspan="6">Recorded Where?</th>
		<th colspan="2">Home (Studio) Mix</th>
		<th>1</th>
		<td><a href="#a1">A1</a></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<th rowspan="5">Live Mix</th>
		<th>Radio</th>
		<th>2</th>
		<td><a href="#a2-a3">A2</a></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<th>Streaming Platform</th>
		<th>3</th>
		<td><a href="#a2-a3">A3</a></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<th>Venue</th>
		<th>4</th>
		<td><a href="#a4">A4</a></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<th>Event Series</th>
		<th>5</th>
		<td><a href="#a5">A5</a></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
	<tr align="center">
		<th>Festival</th>
		<th>6</th>
		<td><a href="#a6">A6</a></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
</table>

<h2>Naming Precedence</h2>
`NAMED_HOSTS` have precedence.  

<h2>Individual Cases</h2>
Information inside brackets (`[]`) is optional. 

*Placeholder terms* are written in uppercase with spaces substituted with underscores (`LIKE_THIS`), while *literal terms* are written capitalized using spaces (`Like This`).

<h3 id="a">A - Mixes Hosted by an Artist, Platform, or a Label</h3>
<h4 id="a1">A1</h4>
`MIX_NAME`

The most basic case where mix usually has a name.

<h5>Boiler Room</h5>
Working on this...

<h4 id="a2-a3">A2 / A3 - Radio Booths & Streaming Platforms</h4>
`RADIO_NAME`  
`STREAMING_PLATFORM_NAME`

Live recordings from radio booths and streaming platforms. Notable examples are **The Lot Radio** (Brooklyn), now defunct **Red Light Radio** (Amsterdam), **Future Intel** (The Hague), and **HÖR** (Berlin).  

<h4 id="a4">A4 - Venue Recordings</h4>
`VENUE_NAME`&nbsp;[`(FLOOR_NAME)`]&nbsp;`,`&nbsp;&nbsp;`CITY_NAME`

Examples:
> "Tresor, Berlin"  
> "Tresor (Globus), Berlin  
> "Bassiani, Tbilisi"  
> "Bassiani (Horoom), Tbilisi  
> "fabric, London"  
> "Fuse, Brussels"  
> "Sub Club, Glasgow"  

<h4 id="a5">A5 - Event Series</h4>
`EVENT_SERIES_NAME`&nbsp;`@`&nbsp;`VENUE_NAME`&nbsp;`,`&nbsp;&nbsp;`CITY_NAME`  

Examples:
> Patterns of Perception @ ://about blank, Berlin  
> Klubnacht @ Berghain, Berlin  
> Vault Sessions @ BRET, Amsterdam  
> CALMA @ Zapadores, Madrid

<h4 id="a6">A6 - Festivals</h4>
`FESTIVAL NAME`&nbsp;`{YEAR}`[`:`&nbsp;&nbsp;`STAGE_NAME`][^1]  
`FESTIVAL NAME`&nbsp;`EDITION_NAME`&nbsp;`YEAR`[`:`&nbsp;&nbsp;`STAGE_NAME`][^2]

Examples:
> Dekmantel Festival 2017   
> Burning Man 2014: Robot Heart  
> CRSSD Festival Spring 2015  
> CRSSD Festival Fall 2022

<h3 id="b">B - Podcasts & Mix Series</h3> 
`PODCAST_NAME`  
`PODCAST_NAME`&nbsp;`{ENUMERATION}`

<h3 id="c">C - Radio Guest Mixes</h3>
`RADIO_NAME`

Radio mixes which are not part of some radio show.

<h4>NTS Radio Guest Mixes</h4>
URL for NTS Radio guest mixes looks like this: `https://www.nts.live/shows/guests ...`.

<h3 id="d">D - Radio Shows</h3>
`RADIO_SHOW_NAME`

Radio shows that have a name, which is *not* a host's name.

Examples:
> Beats in Space  
> 88 Transition  
> The Space Between Spaces

<h4>NTS Radio Shows</h4>
URL for NTS Radio guest mixes looks like this: `https://www.nts.live/shows/RADIO_SHOW_NAME`.

<h3 id="e">E - Radio Residencies</h3>
`HOST_NAME`&nbsp;`'s`&nbsp;`RADIO_NAME`&nbsp;`Show`

Residency shows hosted by artists, labels, collectives, and event promotions. In order to differentiate them from guest mixes (C), the resident's name is included in the title and written in possessive form.

Time slot for these shows is usually 1 or 2 hours. If host is inviting guests in a longer time slot, this runtime is usually split equally between them, i.e. an hour each.  

Examples (artist-hosted):
> SPFDJ's Rinse FM Show  
> Bicep's NTS Radio Show  
> DJ Nobu's NTS Radio Show

Examples (collective-hosted):
> MARICAS' Rinse FM Show

Examples (label-hosted):
> Hessle Audio's Rinse FM Show  
> Huntleys + Palmers' Rinse FM Show

<h4>NTS Radio Residency Shows</h4>
URL for NTS Radio residency shows looks like this: `https://www.nts.live/shows/HOST_NAME`.
<h4>Rinse FM Residency Shows</h4>
Rinse FM lists all their current shows at [rinse.fm/shows/](https://rinse.fm/shows/), where show-specific URL looks like this: `https://rinse.fm/shows/HOST_NAME`.


[^1]: Annual festival
[^2]: Biannual festival, rarely triannual
