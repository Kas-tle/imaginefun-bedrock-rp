[![GitHub Super-Linter](https://github.com/Kas-tle/imaginefun-bedrock-rp/workflows/Lint%20Code%20Base/badge.svg)](https://github.com/marketplace/actions/super-linter)
# ImagineFun Bedrock Resource Pack
Resource pack for the ImagineFun Bedrock server.

This resource pack has been merged with [GeyserOptionalPack](https://github.com/GeyserMC/GeyserOptionalPack), a resource pack developed to extend the functionality of the [Geyser](https://github.com/GeyserMC/Geyser) proxy, which ImagineFun utilizes to provide its Bedrock server. See the linked repository for specific [developer documentation](https://github.com/GeyserMC/GeyserOptionalPack/blob/master/developer_documentation.md) with regards to any optional pack components. Components from this pack are included under the MIT license, for which notice is provided.

### Installing
 - Download the latest release of the resource pack from the [releases](https://github.com/Kas-tle/imaginefun-bedrock-rp/releases/latest) tab.
 - Open the mcpack file with your Bedrock client. These steps will vary by platform.
 - Open settings from the main menu screen and navigate to the "Global Resources" tab.
 - Under the "My Packs" list, select the ImagineFun pack and hit "Activate".
 - Platform specific notes:
   - **iOS**:
     - Select "Open in Minecraft" after clicking the .mcpack file in releases.
     - Once Minecraft opens, wait for a message at the top of the screen stating the pack was successfully imported.
   - **Android**
     - After download the file, copy it from your downloads area.
     - From the file exploer of your choice, navigate to the games folder. This may be under your internal storage or on an SD card depending on your setup.
     - Navigate to `~/games/com.mojang/resource_packs`.
     - Place your the .mcpack file in the `resource_packs` folder.
     - [Video Tutorial](https://www.youtube.com/watch?v=dhgAYTmmH7U)
   - **XBox**
     - Resource packs are not supported on XBox, but you can attempt to follow the workaround in this [tutorial](https://www.youtube.com/watch?v=NqzeCGklAp8).
     - Alternatively, if you have an [XBox Developer Account](https://developer.microsoft.com/en-us/store/register/), you can activate your XBox in [developer mode](https://docs.microsoft.com/en-us/windows/uwp/xbox-apps/devkit-activation) and use the file browser in the [Device Portal](https://docs.microsoft.com/en-us/windows/uwp/xbox-apps/device-portal-xbox) to directly access your system files and install the pack.
     - The location of resource packs on XBox is `~/Local/packages/Microsoft.MinecraftUWPConsole_8wekyb3d8bbwe/LocalState/games/com.mojang/resource_packs`
   - **Windows**
     - Press Win+R
     - Enter the directory: `%localappdata%\Packages\Microsoft.MinecraftUWP_8wekyb3d8bbwe\LocalState\games\com.mojang\resource_packs`
     - Place your the .mcpack file in the `resource_packs` folder.
     - [Video Tutorial](https://www.youtube.com/watch?v=6iq9ps9uPYE)
   - **Platform Agnostic Method**
     - If all else fails, you could run a server on your local network and define the resource pack as the current version of this pack from the releases tab. After joining the created server once, your client will cache the pack, and this cache can be accessed whenever a resource pack is required by a server.
     - I have temporarily created a server to facilitate this process, primarily for console users who must use BedrockConnect to join. The direct IP is: `95.217.113.104`.
       - First, join `95.217.113.104` using [BedrockConnect](https://github.com/Pugmatt/BedrockConnect). Note that currently, due to Sony doing some degree of DNS traffic regulation, you must use a local instance of BedrockConnect if attempting to connect on a PS4. Refer to their linked repo to facilitate this.
       - Accept the resource pack and wait for the download to complete before disconnecting.
       - Connection to `bedrock.imaginefun.net` should now proceed normally without a pack download, as the resource pack is now cached locally.

### Find Out More
  - Join the server at `bedrock.imaginefun.net`
  - Join the Discord at https://discord.gg/disneyland.
  - Find out more at https://imaginefun.net/.

### Notice
No copyrights are claimed for the assets contained in this pack, and all content is expressly owned by the original copyright holder.
