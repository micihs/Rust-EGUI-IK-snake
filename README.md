# inverse-kinematics

This is a Rust adaptation of a snake-like GUI to learn the egui library and apply some knowledge of Inverse kinematics as it applies to tracking changes along a series of segments of N + 3 joints.

About application in a nutshell: You can generate "snake" with different parameters and its "head"
will follow your cursor. make changes to the width and number of segments via the 'settings' menu.

To play with this, make sure you have [egui dependencies](https://github.com/emilk/egui)
installed, then run `cargo run --release`.

To try it on web, run `./start_web`. Run `./setup_web.sh` if you're compiling this for the first time.
Actual webpage is deployed on `gh-pages` branch.


