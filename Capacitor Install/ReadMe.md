# Install the Capacitor CLI locally
npm install -D @capacitor/cli
# Initialize Capacitor in your React project
npx cap init
# Install the required packages
npm install @capacitor/core @capacitor/ios @capacitor/android
# Add the native platforms
npx cap add ios
npx cap add android