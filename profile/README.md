## MauiGtk Community 🐧🏝️

We are the **MauiGtk Community**, a group dedicated to making .NET MAUI work on Gtk.
We think that a GitHub org is the logical next step to make it possible to sustainably support this platform.
Everyone who wants to contribute is welcome: Here is the place to gather individuals who submitted pull request for maui on Gtk and related repos in the past -- and those who are eagerly trying to become capable to do so. And maybe it will evolve to a point where we can make strategic decisions, e.g. on how to keep the platform open towards Gtk4 and future versions of Gtk.

It all started with **Mono Touch** that emerged as part of the open source alternative to .NET -- let's bring it home to **the** open source operating system, where it belongs. ✨

### Main Projects 💻

- [@MauiGtk version](https://github.com/MauiGtk/maui-linux): Main repository (Former [@jsuarezruiz](https://github.com/jsuarezruiz) version)
- [@lytico version](https://github.com/lytico/maui): Reference
- [Mali](https://github.com/nblockchain/Mali): Reference (.NET6)

### Dev Container 📦

- [maui-docker](https://github.com/MauiGtk/maui-docker) -- a planin Dockerfile to build GtkSharp and MAUI and run the samples.
- [maui-devcontainer](https://github.com/Thomas-Mielke-Software/maui-devcontainer) -- work in progress. Currently Thomas is stuck trying to adapt the official cake script so it builds the Gtk platform.
- [maui-podman](https://github.com/Lemon73-Computing/maui-podman) -- just like maui-docker, but using podman.
- [some Gtk Workload](https://github.com/HavenDV/Gtk) -- this includes another Gtk workload approach and has nothing to do with what Trung did for GtkSharp.

### Useful Resources 📄

- [CI/CD](https://github.com/lytico/maui/blob/6ef7f0c066808ea0d4142812ef4d956245e6a711/.github/workflows/build-gtk.yml#L22-L31) -- Lytico's MAUI CI for gtk workload installation.
- [GtkSharp Quick Reference](https://ksvi.mff.cuni.cz/~dingle/2021-2/prog_2/gtk_reference.html) -- useful link to know the Gtk API while implementing new controls
- [gir.core](https://github.com/gircore/gir.core) -- A code generator that produces C# stubs for GObjects (as in Gtk oder GStreamer, for example). This could replace GtkSharp to allow support of Gtk4.
- [GnomeMaui](https://github.com/GnomeMaui) -- Ferenc Czirok's repo shows how to implement a Gtk4 backend for MAUI based on gir.core. Cheers! Definitely worth giving it a star.
- [Xamarin.Forms Progress](https://github.com/jsuarezruiz/forms-gtk-progress/issues) -- This is the backend predecessor of maui-linux based on Xamarin.Forms and Gtk2.

### Community 🧑‍🤝‍🧑

- [GitHub](https://github.com/MauiGtk) (here)
- [Matrix](https://matrix.to/#/#maui-linux:matrix.org) (WebChat)
- Website
  - [Official MauiGtk Website](https://mauigtk.net) (Promotion, Blog)
  - [Alternative Wordpress Website](https://maui-linux.net/) by [@Ten](https://github.com/TenEniunlsl) (Wiki, Blog)
- Mastodon
  - [@mauigtk@fosstodon.org](https://fosstodon.org/@mauigtk) (Main)
  - [@mauilinuxnet@mastodon.social](https://mastodon.social/@mauilinuxnet) (belongs to [@Ten]s website)

### What's Brewing Currently

* 2026-01-05: Added some context to the links on this overview page.
* 2025-11-28: We officially have sent a project proposal to PrototypeFund to get funding. \o/ Thanks to Mathias for reviewing the application text!
* 2025-11-24: Website was launched on https://mauigtk.net -- now have some patience until it gets some content!
* 2025-11-22: Working on setting up a static website.
* 2025-11-20: Follow our Mastodon account on https://fosstodon.org/@mauigtk to stay informed about our progress!
* 2025-11-19: We had our 2nd video call on 19th of November where we focused on a first public funding attempt. Will meet again in January.
