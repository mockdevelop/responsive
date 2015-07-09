A Pen created at CodePen.io. You can find this one at http://codepen.io/ericam/pen/DpmGt.

 The underlying code creates CSS Tabs controlled by radio/checkbox inputs. That part is simple, and has been done before.

What was new for me was discovering how I could use the float isolation method to layer all the tab content on the z-axis, keeping the container responsive to all the content, even the hidden tabs.

- Container wraps all tabs dynamically
- Container size remains equal across tabs
- No JS Height calculations
- The entire thing is responsive
