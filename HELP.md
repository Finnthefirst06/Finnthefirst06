# CoreScope quick help

For CoreScope 7.9.6. Hardware support depends on the device, its driver and how it is connected.

## A temperature shows a dash

A dash means that a reading is unavailable, not zero degrees. Open **Settings → Updates & help → Set up PC** to review sensor access and the optional driver. If Windows asks for administrator approval, check that you launched your trusted CoreScope installation. A restart may be required after installing a driver.

If antivirus blocks a component, keep protection enabled and record the exact detection name and filename for investigation. Do not download replacement drivers from random sites. Some systems do not expose all sensors even with the required permissions.

## RGB is missing or does not change

1. Open **Lighting → Compatibility & help**, then check the device in OpenRGB. CoreScope cannot add hardware support that OpenRGB lacks.
2. Connect to OpenRGB and select the actual device or header in CoreScope.
3. If a header has no configured LEDs, use **LED setup** and enter the real LED count from the hardware documentation. Count LEDs, not fans; do not guess.
4. Choose a color, then select **Apply**. Previewing alone does not change hardware.
5. If another RGB application keeps overwriting the color, stop its lighting effect before retrying.

A hub can make several fans behave as one device. Independently controlling each fan requires compatible wiring and hardware. Palette animations also require a supported Direct mode. An accepted software command does not prove that the physical LEDs changed.

References: [OpenRGB device support](https://openrgb.org/devices.html) · [LED configuration](https://openrgb.org/resize.html).

## Choose overlay values

Open **Settings → Mini-overlay → Choose values**. Select one value or up to twelve standard readings and favorite sensors. Use search and scrolling for long lists. Adjust size and position with the preview editor, then choose **Apply**. The shortcut can be recorded under **Settings → Hotkey**.

## Update access fails

Downloads are private and require an invited account. Connect through **Settings → Updates & help**; complete sign-in only on the official **github.com** page in your browser. Never type a GitHub password into CoreScope or share the displayed authorization code.

When the app is current, the install button is disabled. For an access error, verify the invited account and accepted invitation. For a network error, restore connectivity and retry. Do not bypass a signature or checksum failure.

**Update setup preserves your settings. Full setup resets them.** Windows may still request administrator confirmation during an update.

## Report a layout problem

Include the app version, Windows display scale, screen resolution, affected tab, and steps to reproduce. Crop screenshots to the app and hide personal paths, account details and authorization codes. Send reports through your existing private testing channel.
