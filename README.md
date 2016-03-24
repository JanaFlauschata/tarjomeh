**Tarjomeh** is a work-in-progress language learning app which allows people to help each other and learn as a tandem.

For example a French native speaker who wants to learn German and a German native speaker who wants to learn French can meet at Tarjomeh and develop their language skills by practicing translations in their mutual languages.

# Planned features

* play translation games with your Tarjomeh friends by choosing a sentence in a language both of you know well (I guess this might be English for the most) and translate it to your learning language
* correct your partner's translation and receive corrections vice versa
* earn points for successful translations and rise levels
* archive your translations for reviewing them later

# Technology

**Tarjomeh** uses custom [Polymer](https://www.polymer-project.org/1.0/) Webcomponents for building the user interface.

The backend uses [Hoodie](http://hood.ie/) for the user management and as an interface to [CouchDB](http://couchdb.apache.org/). So the app needs to be run on a Hoodie server.

It uses some plugins for Hoodie like
* [imagine](https://github.com/nintra/hoodie-plugin-imagine)
* [direct messaging](https://github.com/JanaFlauschata/hoodie-plugin-direct-messages) (fork of existing Hoodie plugin)
* [Tarjomeh languages](https://github.com/JanaFlauschata/hoodie-plugin-tarjomeh-languages) (custom Tarjomeh Hoodie plugin)
* [Tarjomeh profile](https://github.com/JanaFlauschata/hoodie-plugin-tarjomeh-profile) (custom Tarjomeh Hoodie plugin)

# Current status

Currently the basis of the app is being migrated from the former [Firebase](https://www.firebase.com/) backend to Hoodie.

# Screenshots

![Overview](/resources/tarjomeh-large.jpg)

![Friendlist](/resources/friends-mobile.jpg)

![Chat and translation view](/resources/chat-mobile.jpg)

![User profile](/resources/profile-mobile.jpg)
