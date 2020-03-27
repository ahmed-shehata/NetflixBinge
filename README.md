# Netflix Binge iOS App
iOS application to find highly rated TV shows currently available on Netflix along with how long it will take to binge watch all seasons of the show. Particularly useful during the COVID-19 pandemic!

Status: In-Development

![enter image description here](https://lh3.googleusercontent.com/Jj6r3ZOMx5R9COEtQHfV7U3Im9DPLPs6chK-AjZChLp47TLL34ZKLiVYifda8qM9ucsy1bBSaqQ2vbVpcx2TyOTKoIwbzv1XLvDaXHzMcpHeO5k28zbAiIxGCdut-xsutHA7KUjSXmg=w2400).png)

## Installation

You must be using a Mac with Xcode installed. App will be distributed over TestFlight in the near future.

Clone the repo and open NetflixBinge.xcworkspace

Build and run the app on the iOS simulator or connect your iPhone and install directly to your physical device.

## APIs and External Libraries
Unofficial Netflix Global Search API [https://rapidapi.com/unogs/api/unogs](https://rapidapi.com/unogs/api/unogs)
The Movie Database API [https://developers.themoviedb.org/3](https://developers.themoviedb.org/3)
SwiftSoup [https://github.com/scinfu/SwiftSoup](https://github.com/scinfu/SwiftSoup)
SDWebImage [https://github.com/SDWebImage/SDWebImage](https://github.com/SDWebImage/SDWebImage)

## Breakdown

**Fetcher.swift** contains the networking code that talks to the various APIs
**Responses.swift** contains the structs responsible for decoding the JSON response from the API to native Swift objects
**MovieCell.swift** defines the row/cells for the TableView
**MovieTableViewController.swift** contains the code for setting up the main view and registering the cells to the table view, conforms to UITableViewDelegate and UITableViewDatasource protocols

## Meta

CS 411 Software Engineering Team

 - Alexander Sikand
 - Andres Rodriguez
 - Henry Wu
 - Leon Yu

