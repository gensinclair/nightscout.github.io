# Reports

Nightscout offers some fantastic data-crunching report tools in the drawer menu, 

<img src="../img/UseNS21.png" style="zoom:80%;" />

</br>

Select `Reports` to open the reports page.

<img src="../img/Reports00.png" style="zoom:80%;" />

</br>

First select the report type you'd like to see (see below for an overview).

`Day to day`, `Week to week`, `Daily Stats`, `Distribution`, `Hourly stats`, `Percentile Chart`, `Weekly success`, `Calibrations`, `Treatments`, `Profiles` or `Loopalyzer`

Then select the period for which you want your data analyzed.

Enable the check box and either select `From:` and `To: `dates or `Today`, `Last 2 days`, `Last 3 days`, `Last week`, `Last 2 weeks`, `Last Month`, `Last 3 months`.

<img src="../img/Reports01.png" style="zoom:80%;" />

</br>

You can filter your data using key `Notes` or `Event type` (select one in the drop down list).

<img src="../img/Reports02.png" style="zoom:80%;" />

</br>

You can select which week days to use in order to better analyze patterns.

<img src="../img/Reports03.png" style="zoom:80%;" />

</br>

Confirm your `Target BT range` `bottom` and `top` for your TIR and graph range lines.

You can also sort the report from older to newer or newer first.

<img src="../img/Reports04.png" style="zoom:80%;" />

</br>

Click `SHOW` and wait for data to load and rendering to complete. This might take some time if the period is long.

<img src="../img/Reports05.png" style="zoom:80%;" />

</br>

## Day To day

This report will show your BG, day by day, including the treatments you select.

<img src="../img/Reports06.png" style="zoom:80%;" />

</br>

If you want to change selections, you need to click again `SHOW` to update the view.

<img src="../img/Reports07.png" style="zoom:80%;" />

</br>

If you select `Insulin distribution` you will get a short report.

Note: You need `Basal rate` enabled to see bolus vs basal information.

<img src="../img/Reports08.png" style="zoom:80%;" />

</br>

You can change the vertical scale to `Logarithmic` or `Linear`.

You can change the graph `Size`.

<img src="../img/Reports09.png" style="zoom:80%;" />

</br>

## Week to Week

This report will give you a week by week view, with color code for week days selected.

<img src="../img/Reports10.png" style="zoom:80%;" />

</br>

## Daily stats

This report will give you a daily distribution view.

<img src="../img/Reports11.png" style="zoom:80%;" />

</br>

## Distribution

This report will give you a complete distribution view with a lot of information on the dates range you selected.

<img src="../img/Reports12.png" style="zoom:80%;" />

A1c is only a rough estimation that can be very inaccurate and does not replace actual blood testing. The formula used is taken from:Nathan, David M., et al. "Translating the A1C assay into estimated average glucose values." *Diabetes care* 31.8 (2008): 1473-1478.

Time in fluctuation and Time in rapid fluctuation measure the % of time during the examined period, during which the blood glucose has been changing relatively fast or rapidly. Lower values are better.

Mean Total Daily Change is a sum of the absolute value of all glucose excursions for the examined period, divided by the number of days. Lower is better.

Mean Hourly Change is a sum of the absolute value of all glucose excursions for the examined period, divided by the number of hours in the period. Lower is better.

Out of Range RMS is calculated by squaring the distance out of range for all glucose readings for the examined period, summing them, dividing by the count and taking the square root. This metric is similar to in-range percentage but weights readings far out of range higher. Lower values are better.

GVI (Glycemic Variability Index) and PGS (Patient Glycemic Status) are measures developed by Dexcom, detailed [can be found here](https://web.archive.org/web/20160523152519/http://www.healthline.com/diabetesmine/a-new-view-of-glycemic-variability-how-long-is-your-line).

</br>

## Hourly stats

This report will give you an hourly distribution view with a box plot and additional hour by hour statistics.

<img src="../img/Reports13.png" style="zoom:80%;" />

</br>

## Weekly success

This report will give you an weekly view of your statistics.

<img src="../img/Reports14.png" style="zoom:80%;" />

</br>

## Calibrations

This will give you a a table of your calibrations, if your uploader sends the correct event and data.

</br>

## Treatments

This will give you a a table of your treatments, day by day.

<img src="../img/Reports15.png" style="zoom:80%;" />

</br>

## Profiles

This report will display all your [profiles](../nightscout/profile_editor.md).

</br>