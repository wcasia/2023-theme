# WordCamp Asia 2023

Setup guide for the [WordCamp Asia 2023](https://asia.wordcamp.org/2023) theme.

## Set up the theme

- Go to `WP Admin » Appearance » Themes`.
- Select the `CampSite 2017` theme.

## Set up the site identity

- Go to `WP Admin » Appearance » Customize » Site Identity`.
- Set up the site title, tagline and site icon according to your needs.

## Set up the menu

- Go to `WP Admin » Appearance » Menus`.
- Set up the menu(s) according to your needs.

## Set up the widgets

- Go to `WP Admin » Appearance » Widgets`.
- Set up the widgets according to your needs.

## Set up the front page

- Go to `WP Admin » Settings » Reading`.
- In the section `Your homepage displays` select `A static page (select below)`
- Select the front page according to your needs.

## Set up the fonts

- Go to `WP Admin » Appearance » Fonts`.
- In the section `Google Web Fonts` add `@import url('https://fonts.googleapis.com/css?family=Roboto+Slab:400,700|Rubik:400,700&display=swap');`.
- In the section `Font Awesome` add https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css.

## Set up and build the theme

- Install the dependencies using `npm i`.
- Build the theme using `npm run build`.

## WordCamp.org sandbox

If wanted, you can also [setup a local WordCamp.org sandbox](https://make.wordpress.org/community/handbook/wordcamp-organizer/first-steps/web-presence/contributing-to-wordcamp-org/setting-up-a-local-wordcamp-org-sandbox/).

## Known problems

> I applied CSS changes, ran `npm run build`, uploaded the changes to GitHub and cleared the cache. Yet, my changes are not visible on the site.

If this happens, simply head over to https://asia.wordcamp.org/2023/wp-admin/themes.php?page=remote-css, change `Output Mode` to `Replace` and save the changes. Then, change `Output Mode` back to `Add-on` and save again. You should now see the applied changes.

## Questions or suggestions?

Keep 'em coming! Simply open a new issue via https://github.com/wcasia/theme-2023/issues/new.

## Credits

Credit where credit's due! The inital WordCamp Asia 2023 theme is based on the great work of [Dreb Bits](https://github.com/drebbits), [Nidhi Jain](https://github.com/jainnidhi), [Lincoln Islam](https://github.com/appsrex), [Tepken Vannkorn](https://github.com/tepkenvannkorn) & [Witt Witsan](https://github.com/wittwitsan).
