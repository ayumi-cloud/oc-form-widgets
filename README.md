# Form Widgets plugin
This plugin extend the back-end forms to new field types.

## New items
* __Pickadate__ (datepicker and timepicker)
* __TimePicki__ (timepicker)
* __MiniColors__ (colorpicker)

## Documentation

### Pickadate
`pickadate` - renders a text field used for selecting date and times.

    date:
        label: Date
        type: pickadate
        mode: date

Option | Description
------------- | -------------
**mode** | the expected result, either date, datetime or time. Default: datetime.
**selectYears** | display select menus to pick the year. Default: false.
**selectMonths** | display select menus to pick the month. Default: false.
**interval** | choose the minutes interval between each time in the list. Default: 30.

See the demo: [http://amsul.ca/pickadate.js](http://amsul.ca/pickadate.js)

### TimePicki
`timepicki` - renders a text field used for selecting times.

    time:
        label: Time
        type: timepicki
        stepSizeMinutes: 10

Option | Description
------------- | -------------
**increaseDirection** | set increase hour or minute direction. Default: 'down'.
**customClasses** | add custom class name in timepicki for our own like css purpose. Default: ''.
**minHourValue** | set minimum hour which means we can set minimum value of hour. Default: 0.
**maxHourValue** | also can set maximum hour same like minimum hour. Default: 23.
**showMeridian** | you can choose to hide the AM/PM selector. Default: false.
**stepSizeHours** | the step size with which hours have to increase or decrease Default: 1.
**stepSizeMinutes** | the step size with which hours have to increase or decrease Default: 1.
**overflowMinutes** | that hours will be updated if we go over the maximum/minimum of the minutes counter. Default: false.
**disableKeyboardMobile** | prevent keyboard to show up on mobile, side effect: you can't type your hour on desktop keyboard anymore either. Altering hours and minutes with arrows is still possible. Default: false.
**reset** | if want to reset time in input, to enable reset option. Default: false.

See the demo: [http://senthilraj.github.io/TimePicki](http://senthilraj.github.io/TimePicki)

### MiniColors
`minicolors` - renders controls to select a color value.

    theme:
        label: Choose color
        type: minicolors
        control: wheel

Option | Description
------------- | -------------
**animationSpeed** | the animation speed of the sliders when the user taps or clicks a new color. Default: 50.
**animationEasing** | the easing to use when animating the sliders. Default: 'swing'.
**changeDelay** | the time, in milliseconds, to defer the change event from firing while the user makes a selection. Default: 0.
**control** | determines the type of control. Valid options are 'hue', 'brightness', 'saturation', and 'wheel'. Default: 'hue'.
**format** | the format MiniColors should use. Valid options are 'hex' and 'rgb'. Default: 'hex'.
**hideSpeed** | the speed at which to hide the color picker. Default: 100.
**keywords** | a comma-separated list of keywords that the control should accept (e.g. inherit, transparent, initial). Default: ''.
**letterCase** | determines the letter case of the hex code value. Valid options are 'uppercase' or 'lowercase'. Default: 'lowercase'.
**position** | sets the position of the dropdown. Valid options are 'bottom left', 'bottom right', 'top left', and 'top right'. Default: 'bottom left'.
**showSpeed** | the speed at which to show the color picker. Default: 100.

See the demo: [http://labs.abeautifulsite.net/jquery-minicolors](http://labs.abeautifulsite.net/jquery-minicolors)

## Available languages
* en - English
* hu - Magyar

## Credits
* Datepicker: [Pickadate](http://amsul.ca/pickadate.js)
* Timepicker: [TimePicki](http://senthilraj.github.io/TimePicki)
* Colorpicker: [MiniColors](http://labs.abeautifulsite.net/jquery-minicolors)
