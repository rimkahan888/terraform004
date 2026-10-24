Practice dashboard of 54 questions Johan keeps getting wrong, laid out as a card grid with a collapsible right-hand explanation panel (answer, explanation, why the others are wrong, and a simulated terminal run) and a practice mode that tracks mastered and wrong counts in localStorage. Open `index.html` in a browser; no build or network is needed.

Double-click a card to copy the question, exhibit, and options as plain text; a "Qn copied" toast confirms the copy.

The explanation panel always takes half the page: half the width on wide screens, and half the height as a bottom sheet on narrow ones. Smooth sliders set card size (40–100%) and panel text size (50–130%), and both are remembered in localStorage.

![Narrow side panel, half-height explanation sheet and size sliders](screenshots/sidepanel-540-sliders.png)

![Wide layout, half-width explanation panel and size sliders](screenshots/wide-1920x1080-sliders.png)

![Wide layout, explanation panel open](screenshots/wide-1920x1080-panel-open.png)

![Wide layout, explanation panel collapsed](screenshots/wide-1920x1080-panel-collapsed.png)

![Portrait layout, explanation panel open](screenshots/portrait-1080x1920-panel-open.png)
