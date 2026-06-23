## Summary

What does this pull request do, and why?

## Related issue

Fixes #

## Testing

- Game build tested:
- What I verified in-game:

## Checklist

- [ ] Compiles in Release (`cmake --build build --config Release`)
- [ ] No new compiler warnings
- [ ] Guarded all game-memory access with `Mem::IsReadable`
- [ ] Risky calls into game code are wrapped in `try/catch`
- [ ] Heavy / structural work is kept off the render (Present) thread
- [ ] Updated `README.md` / `PROJECT_AND_SDK.md` if behavior changed
- [ ] Kept the SPDX + copyright header on any new source files
- [ ] Single-player only; nothing here targets multiplayer

## Notes

Anything reviewers should know.
