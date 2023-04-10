#### Written by [PablosCorner](https://github.com/PablosCorner) (Last updated: 4/10/2023)

> Food Channel (Deliveroo) currently is only available in **select** EU countries where Deliveroo operates in. More services and regions are being looked at and considered in the future. If you're outside those select EU countries, use **Food Channel (Standard)** or **Food Channel (Domino's)** instead.

> As Food Channel (Deliveroo) just released, this guide is still a work in progress and will most likely be updated/changed a lot. If you have any questions, feel free to ask in the [WiiLink Discord](https://discord.gg/WiiLink).

I've written this temporary guide to help people properly install Food Channel (Deliveroo) from the WiiLink Patcher, as one doesn't exist on **wii.guide** yet.

#### Supported EU Countries

* United Kingdom
* France
* Belgium
* Ireland
* Italy
* Singapore
* Hong Kong
* United Arab Emirates
* Kuwait
* Qatar

#### What you need

* An SD card or USB drive
* A Wii console with an active internet connection
* A computer with an active internet connection
* A Discord account
* A Deliveroo account
* [WiiLink Patcher](https://github.com/WiiLink24/WiiLink24-Patcher/releases)
* [Deliveroo Helper](https://github.com/WiiLink24/DeliverooHelper/releases)

##### Section I - Getting Started

1. Make sure to download the version of the WiiLink Patcher that corresponds to your operating system.
2. Launch the patcher and begin the setup process.
3. When you see the setup screen, select `1. English Translation` in order to gain access to the Food Delivery Channel (Deliveroo) channel.<br><br>
![Express Install](https://i.imgur.com/wfSKwFc.png)
4. Next, you’ll see this screen, asking which version of Food Delivery Channel you want, so you’ll want to pick `3. Deliveroo (Select EU countries only)`<br><br>
![Food Delivery Channel Setup](https://i.imgur.com/xg2C9OH.png)
5. After that, you can go through the rest of the process, but once you reach this step, be sure to pick the correct console platform you’re installing this on, as it will matter when using the app.<br><br>
![Console Platform](https://i.imgur.com/zkj7kB1.png)
> If you're installing this on Dolphin Emulator, please be aware that Food Channel (Deliveroo) will not work on the default Dolphin NAND, you will **need** to dump a NAND from your real Wii console. Then you can install your NAND on Dolphin by going to<br>`Tools => Manage NAND => Import BootMii NAND Backup`.

##### Section II - Registering your Console ID

1. After completing the setup process, turn on your Wii and launch the Homebrew Channel.
2. Use the `Get Console ID` Homebrew app, that was given by the patcher, to retrieve your system's console ID.
3. Save the console ID for the next section, as you will need it.

##### Section III - Setting up Deliveroo

1. Get the Deliveroo app on your phone via the [App Store](https://apps.apple.com/us/app/deliveroo-food-delivery-app/id1001501844) or [Google Play](https://play.google.com/store/apps/details?id=com.deliveroo.orderapp).
2. Create an account and add your address and payment information.
3. Give your address a label named `demae` (all lowercase).<br><br>
![Deliveroo Address Label](https://i.imgur.com/Imn8bpO.png)
4. Launch the Deliveroo Helper and follow the instructions on the screen.<br><br>
![Deliveroo Helper](https://i.imgur.com/E9TYuwy.png)
5. Add your console ID, from earlier, when prompted, as this will link your console with your Deliveroo account.
6. When prompted, you'll also be asked to enter your Discord ID, which you can find by going to `Settings => Advanced => Developer Mode` and enabling it. Then, right click your name and click `Copy ID`.


##### Section IV - Installing WADs

You will now install the Food Delivery Channel and Set Personal Data channels.

1. Put your SD card or USB drive in your Wii.
2. After registering your console ID, go to the Homebrew Channel and launch **Wii Mod Lite**.
3. In the WAD Manager menu, locate `Food Channel (Domino's) (English).wad`.
4. Also locate `WiiLink_SPD (Wii).wad` or `WiiLink_SPD (vWii).wad`, depending on your console platform.
5. Select both WADs by pressing `+` on each one.
6. Press `A` to install the selected WADs.

> If you happen to get `Error -1022` when installing `Food Channel (Domino's) (English).wad`, uninstall the channel by selecting the WAD with `-` and pressing `A`. Then, re-install the WAD.

##### Section V - Setting up Address Information

>WiiLink never stores your personal data. For more information on what is used, read our [Privacy Policy](https://theoldnet.com/get?url=https%3A%2F%2Fdemae.wiilink24.com%2Fprivacypolicy&year=2022&scripts=false&decode=false). (Currently archived, as new page is being worked on)

For this particular version of Food Delivery Channel, you don't have to have accurate address information, as that is needed to be set up on the Deliveroo app. However, you'll still need to go to the menu first before you can use Food Delivery Channel.

1. Launch the Food Delivery Channel from the Wii Menu.
2. If you have not previously set your address information, a prompt telling you to set it will appear. Press the `Address Info` button. Otherwise, click the `Change Address Information` button in the main menu.
3. Now you are in the Address Information menu. Press the arrows to traverse screens. Here you can enter your data, if you wish. When you are finished, click the `Done` button and then `Demae`.<br><br>
![SPD Page 1](https://wii.guide/images/Demae-Dominos/spd-1.png)<br><br>
![SPD Page 2](https://wii.guide//images/Demae-Dominos/spd-2.png)

##### Section VI - Placing an order

> This section requires you to have your payment information set up on the Deliveroo app.

> If you have used the standard version of the Food Delivery Channel before, go to the<br>`Wii Menu settings` -> `Data Management` -> `Save Data` -> `Wii`, then find the <br>Food Delivery Channel icon and click "Erase" to delete the existing save data.

> If you have previously placed an order, skip to step 4.

1. Launch the Food Delivery Channel (aka. Food Channel) from the Wii Menu
2. Follow the on-screen instructions, then click `Order` in the main menu.<br><br>
![Main Menu](https://wii.guide/images/Demae-Dominos/success.png)<br><br>
3. You will now be prompted to select your region. Be sure to select your residing country correctly. Failure to do so will result in restaurants failing to load. You will then be prompted to select your region, then city. If your city is not on the list, you can select any one as it does not matter.
4. Click the button of the category of food you'd like. This will load all the restaurants in your area for that category. The first restaurant in the list is the one closest to you.
5. Click `See Menu` to list the different menu categories. Click the category you would like, then select a food item. In the item screen, you can add toppings and adjust quantity.
6. After adding a food item, you will be brought to the basket. To add a food item, scroll to the bottom and select `Add Order`. To proceed to checkout, click `Next`.
7. Review your order throughly before placing the order. When you are ready, click the big green `Order` button.<br><br>
![Before Order](https://wii.guide/images/Demae-Dominos/order.png)<br><br>
8. If no error appeared, your order was placed, however, before it can be placed successfully, you will recieve a direct message from the `Deliveroo Bot` to confirm your order. You'll need to enter the message provided to successfully place your order as a reply to the bot's message.<br><br>
![Order Confirmation](https://i.imgur.com/7GUPSsU.png)<br><br>

***Happy ordering!***

> If you still encounter any issues using the channel, first look back at the guide and see if you missed anything, and if you still have any issues by then, please join our [Discord server](https://discord.gg/WiiLink) and create a support thread in the `demae-support` forum.