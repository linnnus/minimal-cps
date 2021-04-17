# Minimal CPS counter
This CPS counter was made out of spite. No CPS counter needs a fucking
ripple effect and yet that is exactly what you'll find on the top
search results. That's absurd.

This site tries to mimic a very specific behaviour which is supposed
to be nice. I don't know, I'm not a Epic Gamer™. Even if this
behaviour's wack, my point still stands.

## TODO
* Better cross-browser compatibility
* This has __big__ performance issues. We're doing a lot more work
  than just incrementing a variable on each click, which is why it
  performs so poorly. I don't think there's any way we can achieve
  this behaviour more efficiently than we already do.

  On my computer it takes something like 9.2 ms to handle a click,
  which is pretty horrible compared to how fast some of these people
  click.

  Maybe we should make a new branch which just worked like most others
  do.
