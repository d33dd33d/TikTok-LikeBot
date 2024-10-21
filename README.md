# TikTok Like Bot (WORKING!)

Welcome to the **TikTok Like Bot**! This Python script lets you send likes to TikTok videos using multiple threads.

![TikTok Like Bot](https://i.imgur.com/or4qwxm.png)
**(UPDATED 10/2024)**

---

## How to Use

Here’s how to get the TikTok Like Bot up and running:

1. **Add Your Session IDs**:
   - Open the `sessions.txt` file in the same folder as the bot script.
   - Make sure to put your valid TikTok session IDs in there, one per line. It should look something like this:

       ```text
       sessionid1
       sessionid2
       sessionid3
       ```

2. **Run the Bot**:
   - To start sending likes, just run the script with Python:

       ```bash
       python main.py
       ```

3. **Enter the Video ID**:
   - When the bot asks for it, type in the **Video ID** of the TikTok video you want to like. The bot will take care of the rest using the session IDs you added!

The bot sends likes using multiple threads (default is 125) to speed things up. It’ll keep trying to send likes with all your session IDs until it gets a response.

---

## Note

Good news! All the modules used in this script are built into Python, so you don’t need to install anything extra.

---

## Disclaimer

This bot is for **educational purposes only**. Be careful with how you use it, as manipulating likes on TikTok is against their rules. The author and contributors aren’t responsible for any issues that come from using this script.

---

## License

This project is licensed under the [MIT License](LICENSE).