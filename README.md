[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) [![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg)](code_of_conduct.md)

# Project Connect App

## 💡 Motivation

The goal of this project is to crowdsource and gamify the validation of geolocation data for schools around the world. We need as much help as we can get by looking at satellite imagery at predefined GPS coordinates, and corroborate whether what the user is seeing could be a school or not.

This effort is framed within [Project Connect](https://www.projectconnect.world/), run by the [UNICEF Office of Innocation](https://www.unicef.org/innovation/),  with the goal of knowing where schools are and how connected they are to inform programs around education, health and emergencies. Project Connect emerged out of a need that was expressed by many UNICEF partners and UNICEF Country Offices.

## 🎮 App

The app is live at https://projectconnect.app for anyone to play!

## 📂 Roadmap
[![](docs/roadmap.svg)](https://mermaid-js.github.io/mermaid-live-editor/#/edit/eyJjb2RlIjoiZ2FudHRcbiAgdGl0bGUgUm9hZG1hcFxuICBkYXRlRm9ybWF0IFlZWVktTU0tRERcbiAgYXhpc0Zvcm1hdCAgJWItJVlcbiAgc2VjdGlvbiBQaGFzZSAxXG4gIDEuIENyZWF0ZSBGcm9udCBFbmQgOmRvbmUsIDIwMjAtMDgtMDEsIDYwZFxuICAyLiBDcmVhdGUgQmFjayBFbmQgIDpkb25lLCAyMDIwLTA4LTAxLCA2MGRcbiAgMy4gRHluYW1pYyBpbWFnZXMgOmRvbmUsIDIwMjAtMDgtMDEsIDYwZFxuICA1LiBEZXBsb3kgKyBsYXVuY2ghIDpkb25lLCAyMDIwLTA4LTAxLCA2MGRcblxuICBzZWN0aW9uIFBoYXNlIDJcbiAgMS4gU2F0ZWxsaXRlIEltYWdlcnk6MjAyMC0xMC0wMSwgOTBk4oCLXG4gIDIuIFVzZXIgTWFuYWdlbWVudCA6YjIsIDIwMjAtMTAtMDEsIDkwZOKAi1xuICAzLiBHYW1pZmljYXRpb24gOmIzLCAyMDIwLTEwLTAxLCA5MGTigItcbiAgNC4gSW5jZW50aXZpemF0aW9uIDpiNCwgMjAyMC0xMC0wMSwgOTBk4oCLXG4gIDUuIEludGVncmF0aW9uIC0-IFByb0NvIDIuMCDigIs6YjUsIDIwMjAtMTAtMDEsIDkwZOKAi1xuIFxuICBzZWN0aW9uIEZ1dHVyZVxuICAxLiBGZWVkYmFjayBnYXRoZXJpbmc6MjAyMS0wMS0wMSwgOTBk4oCLXG4gIDIuIERlc2lnbiAmIGZ1bmN0aW9uYWwgdXBkYXRlcyA6MjAyMS0wMS0wMSwgOTBk4oCLXG4gIDMuICsgb3RoZXIgZGF0YSBhZ2dyZWdhdG9ycyAtPiBNTCBtb2RlbHMgOjIwMjEtMDEtMDEsIDkwZOKAiyIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0IiwidGhlbWVWYXJpYWJsZXMiOnsiYmFja2dyb3VuZCI6IndoaXRlIiwicHJpbWFyeUNvbG9yIjoiI0VDRUNGRiIsInNlY29uZGFyeUNvbG9yIjoiI2ZmZmZkZSIsInRlcnRpYXJ5Q29sb3IiOiJoc2woODAsIDEwMCUsIDk2LjI3NDUwOTgwMzklKSIsInByaW1hcnlCb3JkZXJDb2xvciI6ImhzbCgyNDAsIDYwJSwgODYuMjc0NTA5ODAzOSUpIiwic2Vjb25kYXJ5Qm9yZGVyQ29sb3IiOiJoc2woNjAsIDYwJSwgODMuNTI5NDExNzY0NyUpIiwidGVydGlhcnlCb3JkZXJDb2xvciI6ImhzbCg4MCwgNjAlLCA4Ni4yNzQ1MDk4MDM5JSkiLCJwcmltYXJ5VGV4dENvbG9yIjoiIzEzMTMwMCIsInNlY29uZGFyeVRleHRDb2xvciI6IiMwMDAwMjEiLCJ0ZXJ0aWFyeVRleHRDb2xvciI6InJnYig5LjUwMDAwMDAwMDEsIDkuNTAwMDAwMDAwMSwgOS41MDAwMDAwMDAxKSIsImxpbmVDb2xvciI6IiMzMzMzMzMiLCJ0ZXh0Q29sb3IiOiIjMzMzIiwibWFpbkJrZyI6IiNFQ0VDRkYiLCJzZWNvbmRCa2ciOiIjZmZmZmRlIiwiYm9yZGVyMSI6IiM5MzcwREIiLCJib3JkZXIyIjoiI2FhYWEzMyIsImFycm93aGVhZENvbG9yIjoiIzMzMzMzMyIsImZvbnRGYW1pbHkiOiJcInRyZWJ1Y2hldCBtc1wiLCB2ZXJkYW5hLCBhcmlhbCIsImZvbnRTaXplIjoiMTZweCIsImxhYmVsQmFja2dyb3VuZCI6IiNlOGU4ZTgiLCJub2RlQmtnIjoiI0VDRUNGRiIsIm5vZGVCb3JkZXIiOiIjOTM3MERCIiwiY2x1c3RlckJrZyI6IiNmZmZmZGUiLCJjbHVzdGVyQm9yZGVyIjoiI2FhYWEzMyIsImRlZmF1bHRMaW5rQ29sb3IiOiIjMzMzMzMzIiwidGl0bGVDb2xvciI6IiMzMzMiLCJlZGdlTGFiZWxCYWNrZ3JvdW5kIjoiI2U4ZThlOCIsImFjdG9yQm9yZGVyIjoiaHNsKDI1OS42MjYxNjgyMjQzLCA1OS43NzY1MzYzMTI4JSwgODcuOTAxOTYwNzg0MyUpIiwiYWN0b3JCa2ciOiIjRUNFQ0ZGIiwiYWN0b3JUZXh0Q29sb3IiOiJibGFjayIsImFjdG9yTGluZUNvbG9yIjoiZ3JleSIsInNpZ25hbENvbG9yIjoiIzMzMyIsInNpZ25hbFRleHRDb2xvciI6IiMzMzMiLCJsYWJlbEJveEJrZ0NvbG9yIjoiI0VDRUNGRiIsImxhYmVsQm94Qm9yZGVyQ29sb3IiOiJoc2woMjU5LjYyNjE2ODIyNDMsIDU5Ljc3NjUzNjMxMjglLCA4Ny45MDE5NjA3ODQzJSkiLCJsYWJlbFRleHRDb2xvciI6ImJsYWNrIiwibG9vcFRleHRDb2xvciI6ImJsYWNrIiwibm90ZUJvcmRlckNvbG9yIjoiI2FhYWEzMyIsIm5vdGVCa2dDb2xvciI6IiNmZmY1YWQiLCJub3RlVGV4dENvbG9yIjoiYmxhY2siLCJhY3RpdmF0aW9uQm9yZGVyQ29sb3IiOiIjNjY2IiwiYWN0aXZhdGlvbkJrZ0NvbG9yIjoiI2Y0ZjRmNCIsInNlcXVlbmNlTnVtYmVyQ29sb3IiOiJ3aGl0ZSIsInNlY3Rpb25Ca2dDb2xvciI6InJnYmEoMTAyLCAxMDIsIDI1NSwgMC40OSkiLCJhbHRTZWN0aW9uQmtnQ29sb3IiOiJ3aGl0ZSIsInNlY3Rpb25Ca2dDb2xvcjIiOiIjZmZmNDAwIiwidGFza0JvcmRlckNvbG9yIjoiIzUzNGZiYyIsInRhc2tCa2dDb2xvciI6IiM4YTkwZGQiLCJ0YXNrVGV4dExpZ2h0Q29sb3IiOiJ3aGl0ZSIsInRhc2tUZXh0Q29sb3IiOiJ3aGl0ZSIsInRhc2tUZXh0RGFya0NvbG9yIjoiYmxhY2siLCJ0YXNrVGV4dE91dHNpZGVDb2xvciI6ImJsYWNrIiwidGFza1RleHRDbGlja2FibGVDb2xvciI6IiMwMDMxNjMiLCJhY3RpdmVUYXNrQm9yZGVyQ29sb3IiOiIjNTM0ZmJjIiwiYWN0aXZlVGFza0JrZ0NvbG9yIjoiI2JmYzdmZiIsImdyaWRDb2xvciI6ImxpZ2h0Z3JleSIsImRvbmVUYXNrQmtnQ29sb3IiOiJsaWdodGdyZXkiLCJkb25lVGFza0JvcmRlckNvbG9yIjoiZ3JleSIsImNyaXRCb3JkZXJDb2xvciI6IiNmZjg4ODgiLCJjcml0QmtnQ29sb3IiOiJyZWQiLCJ0b2RheUxpbmVDb2xvciI6InJlZCIsImxhYmVsQ29sb3IiOiJibGFjayIsImVycm9yQmtnQ29sb3IiOiIjNTUyMjIyIiwiZXJyb3JUZXh0Q29sb3IiOiIjNTUyMjIyIiwiY2xhc3NUZXh0IjoiIzEzMTMwMCIsImZpbGxUeXBlMCI6IiNFQ0VDRkYiLCJmaWxsVHlwZTEiOiIjZmZmZmRlIiwiZmlsbFR5cGUyIjoiaHNsKDMwNCwgMTAwJSwgOTYuMjc0NTA5ODAzOSUpIiwiZmlsbFR5cGUzIjoiaHNsKDEyNCwgMTAwJSwgOTMuNTI5NDExNzY0NyUpIiwiZmlsbFR5cGU0IjoiaHNsKDE3NiwgMTAwJSwgOTYuMjc0NTA5ODAzOSUpIiwiZmlsbFR5cGU1IjoiaHNsKC00LCAxMDAlLCA5My41Mjk0MTE3NjQ3JSkiLCJmaWxsVHlwZTYiOiJoc2woOCwgMTAwJSwgOTYuMjc0NTA5ODAzOSUpIiwiZmlsbFR5cGU3IjoiaHNsKDE4OCwgMTAwJSwgOTMuNTI5NDExNzY0NyUpIn19fQ)

1. **Satellite Imagery**: Our first run of this game during the month of September uncovered some limitations on both how recent some of the images are and the resolution (both of which vary by region). There are active conversations with both the current satellite image provider and alternate providers.

2. **[User Management](docs/user-mgmt.md)**: In order to enable both gamification strategies and incentivization, it is clear that some level of user management is needed. The initial requirements of which are as follows:
    1. Account creation with username and password, and email verification.
    2. Integration with OAuth2 providers: Facebook, GitHub, Google, Instagram, LinkedIn, OpenStreetMap and Twitter
    3. Associating and tracking school tagging activity to each user
    4. Adding new screens for users to manage account and track their activity

3. **User segmentation and Campaign Design**: The basic premise is to define distinct user segments and pilot campaigns tailored to each user segment. There is a current ongoing collaboration with a university class happening throughout the fall semester of 2020. The execution of pilot campaings is blocked by **(1) Satellite Imagery**.

4. **[Gamification](docs/gamification.md)**: Currently exploring a partnership with a game studio company.

5. **Incentivization**: Building financial and non-financial incentives as outlined in [unicef/incentives](https://github.com/unicef/incentives), with a possible blockchain component.

6. **Integration**: Integration with other mapping tools from [Project Connect](https://projectconnect.world), which involve two separate workstreams in the backend and in the frontend. This is blocked by a more mature release of this application including **(1)**, **(2)**, **(3)** and **(4)**.

*Note: The roadmap has been created with [MermaidJS](https://mermaid-js.github.io/mermaid/#/). To update it, do the following:*
1. *Click on the SVG image above, which will open a live editor with the current version (content is encoded in the URL)*
2. *Once you have made the changes, copy the address link of the live editor and update the link above*
3. *On the live editor, click on the link to the SVG, look at the source, and update the [docs/roadmap.svg](docs/roadmap.svg) file*

## 💙 About UNICEF

[UNICEF](https://www.unicef.org/) works in over 190 countries and territories to protect the rights of every child. UNICEF has spent more than 70 years working to improve the lives of children and their families. In UNICEF, **we believe all children have a right to survive, thrive and fulfill their potential – to the benefit of a better world**.

## :memo: License

This software is licensed under the [GNU General Public License](LICENSE) as published by the Free Software Foundation, either version 3 of the License, or
any later version.

```
    ProjectConnect App
    Copyright (C) 2020 UNICEF

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.
```
