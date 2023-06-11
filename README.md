# RateYourMusic: Naming Guidelines for Mixes

This is a nomenclature proposal for [RateYourMusic](https://rateyourmusic.com)'s (RYM) category which encompasses DJ mixes and live electronics. 

This project has **information preservation** as its main goal, since these recordings are often deleted and just temporarily hosted. 

## Taxonomy of Mixes

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
		<th>A</th>
		<th>B</th>
		<th>C</th>
		<th>D</th>
		<th>E</th>
	</tr>
	<tr>
		<th rowspan="6">Recorded Where?</th>
		<th colspan="2">Home (Studio) Mix</th>
		<th>1</th>
		<td align="center">A1</td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
	<tr>
		<th rowspan="5">Live Mix</th>
		<th>Radio</th>
		<th>2</th>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
	<tr>
		<th>Streaming Platform</th>
		<th>3</th>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
	<tr>
		<th>Venue</th>
		<th>4</th>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
	<tr>
		<th>Event Series</th>
		<th>5</th>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
	<tr>
		<th>Festival</th>
		<th>6</th>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
</table>

## Naming Precedence
`NAMED_HOSTS` have precedence.  

## Individual Cases
Information inside brackets (`[]`) is optional. 

*Placeholder terms* are written in uppercase with spaces substituted with underscores (`LIKE_THIS`), while *literal terms* are written capitalized using spaces (`Like This`).

### A - Mixes Hosted by an Artist, Platform, or a Label
#### A1
`MIX_NAME`

The most basic case where mix usually has a name.

##### Boiler Room
Working on this...

#### A2 / A3 - Radio Booths & Streaming Platforms
`RADIO_NAME`  
`STREAMING_PLATFORM_NAME`

Live recordings from radio booths and streaming platforms. Notable examples are **The Lot Radio** (Brooklyn), now defunct **Red Light Radio** (Amsterdam), **Future Intel** (The Hague), and **HÖR** (Berlin).  

#### A4 - Venue Recordings
`VENUE_NAME`&nbsp;[`(FLOOR_NAME)`]&nbsp;`,`&nbsp;&nbsp;`CITY_NAME`

Examples:
> "Tresor, Berlin"  
> "Tresor (Globus), Berlin  
> "Bassiani, Tbilisi"  
> "Bassiani (Horoom), Tbilisi  
> "fabric, London"  
> "Fuse, Brussels"  
> "Sub Club, Glasgow"  

#### A5 - Event Series
`EVENT_SERIES_NAME`&nbsp;`@`&nbsp;`VENUE_NAME`&nbsp;`,`&nbsp;&nbsp;`CITY_NAME`  

Examples:
> Patterns of Perception @ ://about blank, Berlin  
> Klubnacht @ Berghain, Berlin  
> Vault Sessions @ BRET, Amsterdam  
> CALMA @ Zapadores, Madrid

#### A6 - Festivals
`FESTIVAL NAME`&nbsp;`{YEAR}`[`:`&nbsp;&nbsp;`STAGE_NAME`][^1]  
`FESTIVAL NAME`&nbsp;`EDITION_NAME`&nbsp;`YEAR`[`:`&nbsp;&nbsp;`STAGE_NAME`][^2]

Examples:
> Dekmantel Festival 2017   
> Burning Man 2014: Robot Heart  
> CRSSD Festival Spring 2015  
> CRSSD Festival Fall 2022

### B - Podcasts & Mix Series 
`PODCAST_NAME`  
`PODCAST_NAME`&nbsp;`{ENUMERATION}`

### C - Radio Guest Mixes
`RADIO_NAME`

Radio mixes which are not part of some radio show.

#### NTS Radio Guest Mixes
URL for NTS Radio guest mixes looks like this: `https://www.nts.live/shows/guests ...`.

### D - Radio Shows
`RADIO_SHOW_NAME`

Radio shows that have a name, which is *not* a host's name.

Examples:
> Beats in Space  
> 88 Transition  
> The Space Between Spaces

#### NTS Radio Shows
URL for NTS Radio guest mixes looks like this: `https://www.nts.live/shows/RADIO_SHOW_NAME`.

### E - Radio Residencies
`HOST_NAME``'s`&nbsp;`RADIO_NAME`&nbsp;`Show`

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

#### NTS Radio Residency Shows
URL for NTS Radio residency shows looks like this: `https://www.nts.live/shows/HOST_NAME`.
#### Rinse FM Residency Shows
Rinse FM lists all their current shows at [rinse.fm/shows/](https://rinse.fm/shows/), where show-specific URL looks like this: `https://rinse.fm/shows/HOST_NAME`.


[^1]: Annual festival
[^2]: Biannual festival, rarely triannual
