# Discord Container

**Prevent Discord from tracking your visits to other websites**

This is a fork of [Discord Container](https://github.com/containers-everywhere/contain-google)

Discord Container is an add-on you can install on Firefox to prevent Discord from tracking your activity on other websites, so you can continue to use Discord while protecting your privacy.

**Note:** To learn more about Containers in general, see [Firefox Multi-Account Containers](https://support.mozilla.org/kb/containers).

## How does Discord Container work?

The Add-on keeps Discord in a separate Container to prevent it from following your activity on other websites. When you first install the add-on, it signs you out of Discord and deletes the cookies that Discord uses to track you on other websites. 

Every time you visit Discord, it will open in its own container, separate from other websites you visit.  You can login to Discord within its container.  When browsing outside the container, Discord won’t be able to easily collect your browsing data and connect it to your Discord identity.

## How do I enable Discord Container?

We’ve made it easy to take steps to protect your privacy so you can go on with your day.

1. [Install Discord Container](https://addons.mozilla.org/firefox/addon/discord-container/). This will log you out of Discord and delete the cookies it’s been using to track you.
2. Open Discord and use it like you normally would.  Firefox will automatically switch to the Discord Container tab for you.
3. If you click on a link to a page outside of Discord or type in another website in the address bar, Firefox will load them outside of the Discord Container

## How does this affect Discord’s features?

Discord Containers prevents Discord from linking your activity on other websites to your Discord identity. Therefore, the following will not work:

### “Like” buttons and embedded Discord comments on other websites.

Because you are logged into Discord only in the Container, “Like” buttons and embedded Discord comments on other websites will not work.

### Logging in or creating accounts on other websites using Discord

Websites that allow you to create an account or log in using Discord will generally not work properly.

## Will this protect me from Discord completely?

No, discord can still track you while you use their services.

## How do I use Containers for other websites?

Good news! Containers aren’t just for Discord. You can use Containers to prevent websites from linking your identities across the Web by installing [Firefox Multi-Account Containers](https://addons.mozilla.org/firefox/addon/multi-account-containers/).

To learn more about how Mult-Account Containers work, see our support page at [Firefox Multi-Account Containers](https://addons.mozilla.org/firefox/addon/multi-account-containers/).
