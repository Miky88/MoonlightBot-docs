# premium

This command allows you to learn about [MoonlightBot Premium](/support/premium.md) subscriptions and manage your subscription status.

## Required permissions

MoonlightBot requires the following permissions to successfully execute this command:

*No specific permissions required*

By default, a user is required to have the following permissions to use this command:

*No specific permissions required*

For more information on editing permission requirements for specific users/roles, refer to the [permissions tutorial](/start-up/permission-tutorial.md)

## info

This subcommand shows information about Premium subscriptions. Depending on your situation, it will display one of the following:

* **You're not a subscriber**: You'll see the Premium overview, which includes a brief introduction, tier selector buttons above the tier's banner image, a list of benefits for the selected tier, and buttons explaining how to obtain that tier. If you're not eligible for a [volunteer position](/support/volunteering.md) yet, you can ask to be reminded once you are.
* **Your server has a Premium subscription**: You'll see information about the representative of the subscription.
* **You hold a subscription yourself**: You'll see information about your subscription.

{% hint style="info" %}
The overview shown to non-subscribers was completely remade in version 4.8.0, currently available on [MoonlightBot beta](/support/beta.md).
{% endhint %}

```text
/premium info
```

*This subcommand does not have any options*

### Required permissions

MoonlightBot requires the following permissions to successfully execute this subcommand:

*No specific permissions required*

## enable

This subcommand allows a new [Patreon](https://www.patreon.com/MoonlightCapital) subscriber to enable their subscription themselves, without waiting for Staff. To successfully enable your subscription, the following conditions must be met:

* You must be a member of the [support server](https://discord.gg/hNQWVVC).
* Your Discord account must be [connected on Patreon's site](https://support.patreon.com/hc/en-us/articles/212052266-Getting-Discord-access).
* You must have an actual active (paid) pledge on Patreon.

If you change your pledge for extra server slots, run the command again to update your allowance.

After enabling your subscription, if you are on the Advanced tier or higher, you can add the Premium bot to your server. For instructions, see the [activation guide](/support/premium.md#activation).

{% hint style="info" %}
This subcommand was introduced in version 4.8.0, currently available on [MoonlightBot beta](/support/beta.md).
{% endhint %}

```text
/premium enable
```

*This subcommand does not have any options*

### Required permissions

MoonlightBot requires the following permissions to successfully execute this subcommand:

*No specific permissions required*

For more information on editing permission requirements for specific users/roles, refer to the [permissions tutorial](/start-up/permission-tutorial.md).

## Logs

*This command does not trigger any log events*

For more information on setting up those logs, refer to the [log setup tutorial](/README.md#logging)
