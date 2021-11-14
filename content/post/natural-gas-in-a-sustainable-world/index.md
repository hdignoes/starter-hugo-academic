---
title: Natural Gas in a Sustainable World
subtitle: The case for methane as part of a transition to clean energy

# Summary for listings and search engines
summary: Natural gas and natural gas infrastructure can play a key role in a country's transition to clean energy, and might actually be the key to centralized solar power.

# Link this post with a project
projects: [Capstone]

# Date published
date: "2020-12-13T00:00:00Z"

# Date updated
lastmod: "2020-12-13T00:00:00Z"

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: The Motley Fool'
  focal_point: ""
  placement: 2
  preview_only: false

authors:
- admin

tags:
- Academic

categories:
---

## Make no mistake, natural gas is not "clean" energy

Methane combustion, like that of all hydrocarbons, releases carbon dioxide. When someone says that natural gas burns "clean", what they really mean is that it burns completely, i.e. for every molecule of methane burned, we get one molecule of carbon dioxide. But that doesn't mean it's good for the environment. Carbon dioxide from methane combustion actually makes up a sizable chunk of the USA's carbon dioxide (although it doesn't come close to that from transportation). Moreover, methane leaks can actually pose a very serious problem: 1kg of CH<sub>4</sub> has the same effect on global warming as a whopping 84kg of CO<sub>2</sub>! But that doesn't automatically make it bad. Natural gas is among the best understood and most energy-dense fuels we have, and we've been working on ways to burn it as efficiently as possible since the late 1700s. With the world moving towards clean energy sources (wind, solar, hydro...) a big challenge for engineers and policymakers is how the excess capacity should be stored, and how demand can be met when production capacity is low (e.g. at night). This is a particularly popular talking point among political pundits and fossil fuel lobby groups who want to convince the public that solar energy is bad, despite [it being the cheapest source of electricity available](https://www.carbonbrief.org/solar-is-now-cheapest-electricity-in-history-confirms-iea), and having [enormous potential throughout most inhabited regions in the world](https://www.worldbank.org/en/topic/energy/publication/solar-photovoltaic-power-potential-by-country). But they do raise a good point, albeit in bad faith. Variable energy sources, such as solar do have a significant challenge: energy storage. Up until now, this hasn't been a massive issue because fossil fuels are just stored as they are and burned as they're needed.
{{< figure src="https://www.camfil.com/-/media/images/qbank/__web/about-camfil/sustainability/biogas-industryjpg.jpg?rev=1fb08a464ad84e728fd7aa97658bf750&h=641&iar=0&preset=webp&mw=1200&w=1200&hash=03B50ABB664A99AFDD6BF7EE4BCD186B" title="A biogas plant. Photo reprinted from [Camfil](https://www.camfil.com/en-us/insights/energy-and-power-systems/biogas-industry-filtration)." >}}
We do have some forms of energy storage, with the most common being pumped hydropower, where water is pumped into a reservoir such as a dam, storing electrical energy as potential energy. When demand for power rises we can simply let the water flow back down over a set of turbines, generating electrical power. However, this system is not ideal. First of all, it requires massive capital to build these structures, and they aren’t cheap. A typical impoundment dam built to serve a large city can cost significantly more than $5B, and that’s just the initial construction. Maintenance costs can rise quickly since these structures require frequent and meticulous inspection of the dam itself as well as its associated spillways, particularly in areas with heavy rainfall. There are also legislative challenges, as residents and environmental groups are not always happy that their forest, mountain, or even homes will be flooded to make room for these dams. Finally, and perhaps most importantly, this form of energy storage requires a significant height differential. The greater the height, the greater the potential energy and therefore the smaller (and cheaper) you can build your dam for a given energy capacity. This isn’t a problem for places like Canada or Switzerland, where hills and mountains are almost omnipresent, but consider a state like Florida, Minnesota, or Illinois where mountains and prominent hills are relatively rare, and often far from major cities. These places are not well-suited for large-scale pumped hydro, and given its efficiency of around 70%, it’s not a particularly attractive investment for taxpayers. We therefore need an alternative form of energy storage, that is more compact but of similar efficiency. The other obvious form of storage is batteries. It’s easy to think that battery technology has reached the point where widespread usage in a nation’s electrical grid is already here, but that’s simply not the case. They are used, but at the high cost of around $150/kWh, they are only really used to maintain an operating reserve of power or a few hours of peak energy production. They are plagued by lithium and cobalt shortages, relatively low energy densities, and surface phenomena (such as dendrite formation) which can reduce their operational lifetimes and increase their internal resistance. At their best, they boast a respectable 80-90% efficiency, but for the aforementioned reasons, true grid reliance on battery technology is still a good decade away.

Enter the Sabatier reaction. If you’ve read through my capstone project page then you’re already familiar with the Sabatier reaction
{{< figure src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAR4AAABlCAMAAACshXxSAAAAP1BMVEX///8AAAB+fn4+Pj69vb3v7+/Ozs7f398PDw/7+/tubm6enp6Ojo4fHx8vLy9OTk5fX1+urq4yMjIpKSkXFxdDWLEiAAAFhElEQVR4nO2a2WLrKAyGkViHzfjMvP+zjgDvSVMnPW3aRt9FYmNs4I+QELEQDMMwDMMwDMMwDMMwDMMwDMMwDMMwDMP8PIx6dg++B8HUD6xq6Ih2Lh2N7wd58BjxWb17NtaRMH4UZRQiGy0no4lCqHpYsiZLci8rjydBLJAYSYySjGXoxaTHSGYVwLRKrypPNCRPIF0UaKxfrpcbjIG+htTOVHxeD5+JjYLkqboIUKWptLue5HP69U0oYpZHg5KX8siXlicMUeVo26yC6WtXofTJZcIzevd0rFIKojWuOZ3qgsLeXFpcI0dtr97++9FVHoroAr3QSYvhYCchqdf1zGQeiLQi1B5r6DbeX8wiiwOtihjmd6BHHMkXTst72/Ohb4gOrZ+fN/VMjJdDR5c9ShxbDNElRRXvyXmw1zUSALIXPgE4af5Of7foAhJRxijnNuYm32csA+p+KB0ALT5DpnvlzvMZKYPybq++zr0gQpXHppoSUk4o9cleK8DlqAdpCZ9hfTr1mF9aK1Mbc5PvgIManZt/MuhLLYS9DShX6leAsi2Vc622YM3QVxwK3vhRhmNB/iJ5Mkw/azojz84/mKqMhTSdXpdHu+k6wsZ+1HJXy59hHn6C6/Pj2B0cP02ecfuYsAiBd8sztjHmeUTX5fEwLbYsuHXmlMWWLLU0zHWo9nX3k/enZhCfJo/dWvmwNnO3PFbitlvX5UlLr/Om/3KtZLZ1EC6mUa9/ONVbebKq5L81uYZNagGryVcjkBBrU/GUPA29GAVA62bZyaNhSf42kpAgW++9dgLfaHhfimRsG3mcrLi/JY/dxAfYP1RCrk3l8/LgMlCKWJW0k0cBzD+G3Phduau03nJKHtP2be6ZXP+8z+75y5PSUZ47Jld7lFvGfHVy6VX/rSS4SuXrDC9LnWPoKt002uc08WQV/IQ8Vk78ce5feYvk/tueQpoDxOoVtb8pT+jPacYll9mp0zpJrvsetzTgNhNqjVzVEwaYXW96wwS23SGD7OA78jxKWAewxlS18bNnrUdnGrGaxLouT5ntYRe5KERNT8KqWZqcT4+joeTj8vCiO28tC33JH91PH7cPkHNcLkZcyoOHtg7ytEk6XAvsyxCtc12+g8vOfTmp2q9jnOur5vZ/irzc3TwrT0RaaH1w22bXFq3nWz+DX9pYmzTHZchenpLaTJ3OtvIY0mboM2ZaWY3HkE0xHGMZuplYmeLoXdGtcUMXb3S5nqcpdTE1mZGUc+Wa05jBfXjjeNyrq33rZ1XHy9aGaY33glvyhO4CuhehaEdRj1yUo0Ab6hDDNESTcqChX9i8VhjWNbJBjNMspUJM+7pnR6zpEbm8X+8G9pj27fu5Ac1NeW5Rh+jmkxExnM01e4/SYfvgDn+i3BftGBsUR3nC+aa3Qe1ejlvBd6DzJ+xqXKX+O/R4GPjAEL0SjwZpTe7ra7bVFDlel85s+1zDjw93EymxedC9ajlSWvNgu/fzsPXEx4doqr9/8F6/Lhe/AEzysSnykSH+HCgB/ypHxzDMTyOiCbQe1xjqf+gW0daXC6lEYRxbkkaJpUEVxpqWx7uWr7+AEaRRyWh0EZTJWjldlIjKeGEHukryAB05yoHC0HfcX4q6rVCG+koPpckU9LMaBmWtyqOlK9Bf9iFZtHBKaHg186nyUIqr6gaClIhozADOUFndiprlqctfKHT1FeXxsv8TM5Sa1cf6D6Yx7QXMWZ66lqw7RRcJ+29HFmFo2oS21ZbowEojQqwbcWRQVFDAilIzkZDtPXsDvwMZ0Jv2ApStkauQNoEilAm+FhjK8AoqbOajvH814xHum74Y8z1AKK/6RuUZlFUvN2EYhmEYhmEYhmEYhmEYhmEYhmEYhmF+DP8DRQYj1UwKfNkAAAAASUVORK5CYII=" title="Reprinted from Wikimedia " >}}
but just in case I’ll summarize it here. It’ a catalyzed reaction that requires high pressure (ca. 10bar) and high temperatures (400°C is common, but it works just fine around 270°C). Under these conditions using a nickel catalyst, the reaction can achieve almost complete conversion in a PFR, with no side reactions of note. In short, for every mole of carbon dioxide you put in, you get a mole of methane out. But how is this related to energy storage?

Well, the hydrogen required by the reaction has to come from somewhere, and if that somewhere is electrolysis (which can easily be integrated into a solar or wind farm) you are effectively storing clean energy as a fossil fuel. Contradictory, right? There’s a reason why this is desired and can even be better than just storing the hydrogen itself. Natural gas is ubiquitous and has been for the past 20-odd years. Most of the electricity produced in the United States, for example, actually comes from natural gas, not oil or coal as many people think (note: this is electricity, not total energy which includes transportation). The infrastructure is already in place to supply homes with natural gas for heating, store liquefied natural gas, and natural gas power plants are already being upgraded to more efficient furnace models. Pipelines are already in place to move liquefied natural gas to remote communities and across states and provinces. Historically, these have all been part of the fossil fuel industry that is largely responsible for the situation we’re in, but with the Sabatier process, they could be used to transport carbon-neutral energy from a high renewable-producing area (such as BC) to areas with next to no clean energy production (such as Alberta or Saskatchewan). The costs associated with this transition are just the cost of buying electrolyzers and building methanation reactors near industries producing CO<sub>2</sub>-rich streams (i.e. most of them). Far less than the costs of building multiple dams, or massive batteries.

Ultimately, it’s not a perfect solution. It still releases CO<sub>2</sub> back into the atmosphere, and we definitely want to find carbon-negative solutions as we go forward. But for the immediate future? The Sabatier process and natural gas might be our best bet. High energy density, well-understood thermodynamics and physical properties, and a strong total cycle efficiency of over 80% make it an attractive investment that I hope to see gain traction in the next five years.


