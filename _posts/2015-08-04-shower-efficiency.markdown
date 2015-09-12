---
layout: post
title:  "Achieving 81% less shower water usage with a $9 Amazon purchase"
date:   2015-8-4 10:18:00
categories: 
published: true
description: "Looking at our most inefficient use of household water and a simple way to fix it."
image: '/assets/images/shower-efficiency.png'
---

<script src="http://code.highcharts.com/highcharts.js"></script>
<script src="http://code.highcharts.com/modules/exporting.js"></script>

I had a floormate in college who took a shower in about 3-4 minutes. "My dad told me that he paid for the water and I had to use as little as possible", he'd say, as he went to the showers with his loofah already soaped.

I think he even covered himself with soap and turned on the water twice, once for the soap to build lather and the second time to rinse off what he'd applied to himself.

This was insane to me. I thought of the shower as a kind of spa treatment for me, a sort of extended hot tub session where I'd rehash thoughts, come up with ideas, replay memories of the day and sometimes talk the dialog of a conversation I had earlier. Honestly, I was embarrassed. I had been made aware of my privilege with such a simple daily activity. I was taking 'Hollywood showers' my whole life.

Now that I'm a grown-up, pay my own water bills and live in drought ridden Austin, TX, I've paid special attention to water consumption.

## The Navy Shower

I'd later learn about the [Navy shower](https://en.wikipedia.org/wiki/Navy_shower) which was essentially the same thing as what my floormate did.

When you're on a ship, there is a scarce supply of fresh water so showering must be efficient. A Navy shower could use as little as 3 liters of water while a Hollywood shower could use as much as 280 liters. Apparently they call typical showers Hollywood showers.

### How to take a Navy Shower

1. Wet yourself (water on, minimal time)
2. Add water to soap (water on, minimal time)
3. Cover yourself with soap (water off, max time)
3. Rinse (water on, minimal time)

## The Indian Bucket Shower

![Man taking a bucket shower in India](/assets/images/shower-efficiency/bucketshower.jpg "Bucket Shower")
*Man taking a bucket shower in Mumbai. (Rafiq Maqbool/AP)*

Earlier this year when I was in India, I was introduced to the [Indian Bucket Shower](http://www.npr.org/sections/goatsandsoda/2014/07/25/335250270/our-india-correspondent-cant-kick-the-bucket-bathing-habit). Inside one large bucket there is a cup with a handle. You fill up the large bucket and then you ladle water over yourself until you're done. You are much more conscious of how much water you're using.

Cheap traditional guest houses had this setup and probably most households in India. The washing process is the same as the Navy Shower.

## How could I achieve this at home?

I became comfortable with this style of showering. It feels very respectful and efficient. Also it solves the problem of the fogged up mirror when you're trying to shave after a shower. The mirror wont fog up without long periods of running hot water.

The problem for me was the hot/cold mix. I'd love to turn off my shower stream but if I didn't have the proper hot/cold mix, it would just be too much of a pain to readjust it every time with my early 20th century shower controls. I thought there must be a valve that you could put in-between the shower head and the pipe that would allow you to cut off the flow but preserve the hot/cold mix.

Sure enough people on Amazon thought the same.

## The shower head valve

![Shower valve](/assets/images/shower-efficiency/valve.jpg "Shower valve")
*A shower valve ([Amazon.com, $9](http://www.amazon.com/gp/product/B00HSWPYIG/ref=pd_lpo_sbs_dp_ss_1?pf_rd_p=1944687622&pf_rd_s=lpo-top-stripe-1&pf_rd_t=201&pf_rd_i=B0025VWDGQ&pf_rd_m=ATVPDKIKX0DER&pf_rd_r=1QCJAR4PQPSWAEBXK97Q))*

Could this revolutionize the shower? Couldn't I just toggle the shower head valve instead of messing with the hot/cold dials? I could mix the water once and then exclusively use the valve to turn on and off the water!

Turns out that with showers that have the bathtub spigot like mine, water leaks out of the bathtub spigot when the water is on but the shower head valve is closed. My dream was crushed but during a shower, the valve was as effective as I anticipated.

### Installing a shower valve

1. Buy the valve
2. Buy plumber tape
3. Find/buy a wrench
4. [Watch this video](https://www.youtube.com/watch?v=fiv4Zq9v4co) and do what homeboy says

The only tricky part was getting enough plumbers tape on in order for the nozzle not to leak once the valve was cutting off the water. I got it on the 3rd or 4th time.

## Quantifying the result

I've been showering with the valve for months now and have been very happy with it. However, I wanted to go a step further and quantify the water savings.

(Flow rate is 9.2 L / minute)

**A normal shower without the valve.**

* 9 minutes long (water flow only, including warm up and adjustment)
* Used **83 Liters** of water

**A shower with the valve**

* 101 seconds (water flow only, including warm up and adjustment)
* Used **15 Liters** of water 

<div id="water-usage-chart-per-shower" style="min-width: 310px; height: 400px; margin: 0 auto"></div>

## The money savings aren't crazy but they are noteworthy

If you shower every day and live in Austin,TX, you could potentially save around $92 / year on water.

(Combined water and wastewater cost about $0.014 / gallon at peak times)

## Before the valve, showers accounted for the largest proportion of our water usage

Charlotte and I are the only tenants of our place and we do not irrigate our lawn. We do have a washing machine and dishwasher.

Below is a typical usage breakdown of our water usage.

<div id="water-usage-chart-per-household-pre-valve" style="min-width: 310px; height: 400px; margin: 0 auto"></div>

<div id="water-usage-chart-per-household-post-valve" style="min-width: 310px; height: 400px; margin: 0 auto"></div>

Before we installed the shower valve, showers accounted for the most water usage in our house. After the valve was installed, the washing machine became the largest user of water. I had always been curious about this because I knew my washing machine uses a ton of water but we clearly dwarfed it's usage with shower water.

(This accounts for 4 laundry sessions a month. Each session with 2 loads, lights and darks.)

## Why should I care?

At $9, this was probably the most cost-effective and impactful purchase to enable us to conserve water more conveniently. Until crunching the numbers, I didn't grasp how wasteful showering was here.

**'But I don't care about water conservation'**

That's cool ... I guess. You may still find it valuable to stop the flow of water to soap up. I always found it annoying to battle with the incoming water.

You may also find it helpful that the mirror does not fog up if you run the shower for small amounts of time. 

So yeah, I've been very happy with the shower head valve. Let me know if you decide to try one out and save the world with a shower head valve.

![We need a shower head valve to save the world](/assets/images/shower-efficiency/savetheworld.jpg "We need a shower head valve to save the world")
*We need a shower head valve to save the world*

<script>

// Per shower

$(function () {
    $('#water-usage-chart-per-shower').highcharts({
        chart: {
            type: 'column'
        },
        title: {
            text: 'My water savings from Navy style shower'
        },
        xAxis: {
            categories: [
                'Normal Shower',
                'Valve Shower'
            ],
            crosshair: true
        },
        exporting: { enabled: false },
        tooltip: { enabled: false },
        yAxis: {
            min: 0,
            title: {
                text: 'Water Used (L)'
            }
        },
        tooltip: {
            headerFormat: '<span style="font-size:10px">{point.key}</span><table>',
            pointFormat: '<tr><td style="color:{series.color};padding:0">{series.name}: </td>' +
                '<td style="padding:0"><b>{point.y:.1f} L</b></td></tr>',
            footerFormat: '</table>',
            shared: true,
            useHTML: true
        },
        plotOptions: {
            column: {
                pointPadding: 0.2,
                borderWidth: 0
            }
        },
        series: [{
        		showInLegend: false,
            name: 'Water',
            data: [82.782, 15.483]

        }]
    });
});

// Per household pre valve

$(function () {
    $('#water-usage-chart-per-household-pre-valve').highcharts({
        chart: {
            type: 'pie'
        },
        title: {
            text: 'Pre-valve Water Usage in the Crib per month'
        },
        xAxis: {
            categories: [
                'Normal Shower',
                'Valve Shower'
            ],
            crosshair: true
        },
        exporting: { enabled: false },
        tooltip: { enabled: false },
        yAxis: {
            min: 0,
            title: {
                text: 'Water Used (L)'
            }
        },
        tooltip: {
            headerFormat: '<span style="font-size:10px">{point.key}</span><table>',
            pointFormat: '<tr><td style="color:{series.color};padding:0">{series.name}: </td>' +
                '<td style="padding:0"><b>{point.y:.0f} Gal</b></td></tr>',
            footerFormat: '</table>',
            shared: true,
            useHTML: true
        },
        series: [{
        		showInLegend: false,
            name: 'Water',
            data: [
            	{
            		name: "Showers",
            		y: 1308
            	},
							{
            		name: "Washing Machine",
            		y: 360
            	},
							{
            		name: "Dishwasher",
            		y: 24
            	},
							{
            		name: "Sinks and Toilet",
            		y: 116
            	}
            ]

        }]
    });
});

// Per household post valve

$(function () {
    $('#water-usage-chart-per-household-post-valve').highcharts({
        chart: {
            type: 'pie'
        },
        title: {
            text: 'Post-valve Water Usage in the Crib per month'
        },
        xAxis: {
            categories: [
                'Normal Shower',
                'Valve Shower'
            ],
            crosshair: true
        },
        exporting: { enabled: false },
        tooltip: { enabled: false },
        yAxis: {
            min: 0,
            title: {
                text: 'Water Used (L)'
            }
        },
        tooltip: {
            headerFormat: '<span style="font-size:10px">{point.key}</span><table>',
            pointFormat: '<tr><td style="color:{series.color};padding:0">{series.name}: </td>' +
                '<td style="padding:0"><b>{point.y:.0f} Gal</b></td></tr>',
            footerFormat: '</table>',
            shared: true,
            useHTML: true
        },
        series: [{
        		showInLegend: false,
            name: 'Water',
            data: [
            	{
            		name: "Showers",
            		y: 247
            	},
							{
            		name: "Washing Machine",
            		y: 360
            	},
							{
            		name: "Dishwasher",
            		y: 24
            	},
							{
            		name: "Sinks and Toilet",
            		y: 116
            	}
            ]

        }]
    });
});

$(document).ready(function(){
	$('.highcharts-container text:last').hide()
})

</script>




