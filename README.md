# React-native-deployment-on-Iphone
### Archive the app for iOS & android build
- npx expo prebuild
### Install iOS packages for building app in Xcode. 2 Options here:
- 1. npx pod-install     
- 2. cd ios | pod install
### Launch the project with Xcode
- open .
- open {project-name}.xcworkspace
### Sign with Apple account. If needed make own certificate account (details in next step)
- Click on root folder in xcode->Signing & Capabilities
- Team->Select yours
<img width="1080" alt="image" src="https://github.com/user-attachments/assets/45c28219-b697-432d-b2a1-310c61f8aa55" />
### Make account with certificate
- If you dont have create CMD + , or XCode->Settings->Accounts->Make one with certificate
### Allow app to be build and run independantly from MAC
- Product->Scheme->Edit scheme->Build configuration->
  - Run->Build Configuration->Release
  <img width="918" alt="image" src="https://github.com/user-attachments/assets/f9adab25-ec57-4a29-a99e-0f14989f6276" />
  - Archive->Build Configuration->Release 
  <img width="925" alt="image" src="https://github.com/user-attachments/assets/226e3cbe-2033-4181-8c90-4058b8ef9c9d" />
