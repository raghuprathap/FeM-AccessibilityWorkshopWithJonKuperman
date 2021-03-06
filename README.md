# Frontend Masters Accessibility Workshop with Jon Kuperman


## Presenter

Jon Kuperman

* [@jkup on twitter](https://twitter.com/jkup)
* [blog](https://jonkuperman.com/)


## Links

Slides: [The Web is for Everyone - Google Slides](https://docs.google.com/presentation/d/1_CRR-bJFX5Xt-2Tx_lPMDSMUtoxe8s8kAF7DDDXVvc8/edit#slide=id.p)

Repo: [jkup/learn-a11y A web app for learning web accessibility](https://github.com/jkup/learn-a11y)

[WCAG Overview  Web Accessibility Initiative  W3C](https://www.w3.org/WAI/intro/wcag)

[Accessible Color Palette Evaluator](https://accessibility.oit.ncsu.edu/tools/color-contrast/)

[Accessibility Developer Tools - Chrome Web Store](https://chrome.google.com/webstore/detail/accessibility-developer-t/fpkknkljclfencbdbgkenhalefipecmb)

[Tenon.io](https://tenon.io/)

> We believe...
> in a web accessible to everyone. Tenon.io exists because universal
> design is hard. We create software to help you reach beyond
> compliance and build superior experiences for everyone.

[tota11y  an accessibility visualization toolkit](https://khan.github.io/tota11y/)

[Accessibility Evaluation Toolbar  Add-ons for Firefox](https://addons.mozilla.org/en-US/firefox/addon/accessibility-evaluation-toolb/) [Firefox]




## Videos

[Accessibility LIVE - Frontend Masters](https://frontendmasters.com/live-event/accessibility-live/)

The videoplayer also will show the previous videos throughout the
day as they are cut, and they'll live at this address until the
official course is released.

You can click on the little drawer icon in the upper right of the
player to see the videos as they are cut.

![](video-drawer.jpg)



## Other stuff

* [jkup/shortcut - A keyboard shortcut library](https://github.com/jkup/shortcut)
  Jon's open source shortcut library

* [WebAIM Web Accessibility In Mind](http://webaim.org/)
  * [WebAIM WebAIMs WCAG 2.0 Checklist - for HTML documents](http://webaim.org/standards/wcag/checklist)
	this is the checklist Jon is going through in the workshop.

* Vision Simulator [NoCoffee - Chrome Web Store](https://chrome.google.com/webstore/detail/nocoffee/jjeeggmbnhckmgdhmgdckeigabjfbddl)

* [AngularJS API ngAria](https://docs.angularjs.org/api/ngAria#!)

* [react-a11y](https://www.npmjs.com/package/react-a11y)

* [Deque Systems  Web Accessibility  Software, Training, and Consulting](http://www.deque.com/)

* [Accessible Colors  WCAG 2.0 AA and AAA color contrast checker](http://accessible-colors.com/)

* [CSUN Conference 2016 View Sessions](http://www.csun.edu/cod/conference/2016/sessions/)




### Turning on devtools experimental things in Chrome

- Type `about://flags` in the address bar
- Enable Developer Tools experiments
- **Restart** the browser

### other people

* [Jennison Asuncion: @Jennison on Twitter](https://twitter.com/Jennison)


## From the chatroom

### Fri Nov 18 09:47:52 2016

- Jack N: The W3C does a good job showing the breakdown of which WCAG guidelines apply to each role .https://www.w3.org/community/wai-engage/wiki/Accessibility_Responsibility_Breakdown

- Jack N: Here's a useful screen reader compatibility breakdown, http://www.powermapper.com/tests/screen-readers/aria/.

- Daniel D: this is also a thing --> http://vimium.github.io/

### Fri Nov 18 10:20-ish 2016

- Mike N: Do you have a stance on <button> vs <input type="submit"/> for submit buttons?
- Mike N: also enter key on an <input> w/in the form will submit the form IIRC
- Mike N: (will not work with a <button onClick=...> )
- Jack N: A great article about buttons vs. links. https://marcysutton.com/links-vs-buttons-in-modern-web-applications/

### Fri Nov 18 10:58:15 2016

- Victor M: this is really handy: http://keycode.info/

### Fri Nov 18 11:20:27 2016

- Jack N: ARIA describedby, https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/ARIA_Techniques/Using_the_aria-describedby_attribute

### Fri Nov 18 13:25-ish 2016

- Jeremy E: Some helpful ARIA examples here http://heydonworks.com/practical_aria_examples/


### Fri Nov 18 13:29-ish 2016

- Jack N: @Dinesh, if I recall correctly ARIA itself doesn't cause the accessibility tree to be updated. It can announce that a change has occurred. For example, if an AJAX operation occurs, the event happening updates the DOM and accessibility tree. An ARIA live region can be wrapped around it to catch the change and notify a screen reader user.

### Fri Nov 18 14:00:17 2016

- Jack N: (7 minutes ago) Also useful to select color with the correct level of contrast for a specific background color, http://colorsafe.co/.

### Fri Nov 18 15:15:16 2016

- Jeremy E: https://www.udacity.com/course/web-accessibility--ud891
- Jeremy E: A11y Slack channel http://web-a11y.herokuapp.com/
- Jeremy E: Design Systems has a great a11y channel in the Slack team http://designsystems.herokuapp.com/

### Fri Nov 18 15:26:05 2016


- Jack N (7 minutes ago): article about accessibility for UX and design, http://www.uxmatters.com/mt/archives/2014/09/user-experience-and-accessibility-working-with-visual-designers.php
- Jack N (7 minutes ago): 7 Things Every Designer Needs to Know about Accessibility, https://medium.com/salesforce-ux/7-things-every-designer-needs-to-know-about-accessibility-64f105f0881b#.thiyzto8l
- Jack N (5 minutes ago): Web Accessibility for Designers, http://webaim.org/resources/designers/
