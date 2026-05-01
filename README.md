This project is a smart RF receiver board made for things like quiz buzzers, remote switches, or simple automation systems.

Normally, RF receivers can have a problem:
👉 if the signal suddenly stops, the output can get “stuck” ON.
That’s bad, especially in real applications.

So I fixed that.

This board uses a small logic chip (74HC08) to make sure:
✔ the output turns ON only when a signal is actually present
✔ and turns OFF instantly when the signal is gone

So everything works clean and momentary—just like pressing a button.

Another cool thing is the RCA outputs.
They work like simple switches (dry contact), not powered outputs.

👉 That means you can safely connect this board to other systems without worrying about voltage mismatch.

Each channel also has:
💡 a small LED
🔁 a sensing loop (10k resistor)

So you can see if your external device is connected and working. Super helpful during setup.

For power, it runs on a single 18650 battery, and a boost converter keeps everything stable at 5V.
So it’s portable and reliable.

And the PCB?
Designed in KiCad with clear labels, so it’s easy to install and use, even if you're not an expert.

👉 In short:
This is a safe, reliable, no-glitch RF receiver that behaves exactly how you expect—no stuck signals, no confusion.
