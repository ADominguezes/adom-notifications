# \<adom-notifications\>

component that shows notifications in an admin panel

You can change the width notification box with css variable `--adom-notifications-content-min-width` by default is 300px, but it's possible change this.

With the css variable `--adom-notifications-button-icon-size` you can change size of icon. By default is 30px.

Example:

    <adom-notifications icon-notifications="speaker-notes">
    </adom-notifications>

### Styling

The following custom properties and mixins are available for styling:

Custom property | Description | Default
----------------|-------------|----------
`--adom-notifications-content-min-width` | min-width for content box of notifications  | `300px`
`--adom-notifications-content-left` | left for content left | `calc()`
`--adom-notifications-button-icon-size` | size of icon | `30px`
`--adom-notifications` | Empty mixin for notifications | `{}`
`--adom-notifications-button` | Empty mixin for notifications button | `{}`
`--adom-notifications-button-color` | color of notification button | `rgba(17, 17, 17, 0.4)`
`--adom-notifications-button-hover` | Empty mixin for notifications button hover | `{}`
`--adom-notifications-button-focus` | Empty mixin for notifications button focus | `{}`
`--adom-notifications-counter` | Empty mixin for notifications counter | `{}`
`--adom-notifications-counter-background` | background for notifications counter | `#ed1c24`
`--adom-notifications-counter-background` | background for notifications counter | `#fff`
`--adom-notifications-counter-size` | size for notifications counter | `calc()`
`--adom-notifications-content` | Empty mixin for notifications content | `{}`
`--adom-notifications-content-link` | Empty mixin for notifications content link | `{}`
`--adom-notifications-content-link-hover` | Empty mixin for notifications content link hover | `{}`
`--adom-notifications-content-link-focus` | Empty mixin for notifications content link focus | `{}`
`--adom-notifications-arrow` | Empty mixin for notifications arrow | `{}`
`--adom-notifications-box` | Empty mixin for notifications box | `{}`
`--adom-notifications-title` | Empty mixin for notifications title | `{}`
`--adom-notifications-title-background` | background for notifications title | `rgba(17, 17, 17, 0.2)`
`--adom-notifications-title-color` | color for notifications title | `#121212`