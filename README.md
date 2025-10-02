# Unity WebGL Game

This is a Unity WebGL build that can be deployed to any static hosting service.

## Required Build Files

For the game to run properly, the `Build` folder must contain these files:
- `Game.loader.js` - The Unity loader script
- `Game.data.br` - The compressed game data
- `Game.framework.js.br` - The compressed Unity framework
- `Game.wasm.br` - The compressed WebAssembly module

## Deployment Instructions

1. Build the project in Unity with WebGL platform
2. Copy the generated files from the Unity build output to the `Build` folder
3. Commit and push to GitHub
4. Deploy to Vercel or any static hosting service

## Troubleshooting

If the game doesn't load:
1. Check that all required files are present in the `Build` folder
2. Check the browser console for any error messages
3. Ensure the file permissions are correct on your hosting service