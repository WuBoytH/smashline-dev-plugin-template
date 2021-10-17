# smashline dev plugin template
 
Some things to keep in mind:

In your lib.rs, you must change the name in #[skyline::main(name = "Replace with the same name as your plugin")] to be the same as your main plugin's.

Any and all ACMD changes must go into custom/mod.rs due to the limitation of only allowing one #{installer] function in the development plugin.

For any and all other questions, please refer to the smashline wiki, specifically https://github.com/blu-dev/smashline/wiki/The-Development-Plugin.
For any further questions, feel free to DM WuBoy#0238 on Discord.