# React-native-deployment-on-Iphone
# did something..
npx expo run:ios --device device id

npx expo prebuild
npx pod-install
cd ios
open .
open {project-name}.xcworkspace
Click on root folder in xcode->Signing & Capabilities
- Team->Select yours
<img width="1080" alt="image" src="https://github.com/user-attachments/assets/45c28219-b697-432d-b2a1-310c61f8aa55" />

  - If you dont have create CMD + , or XCode->Settings->Accounts->Make one with certificate
- Product->Scheme->Edit scheme->Build configuration->
  - Run->Build Configuration->Release
    <img width="918" alt="image" src="https://github.com/user-attachments/assets/f9adab25-ec57-4a29-a99e-0f14989f6276" />
  - Archive->Build Configuration->Release 
  <img width="925" alt="image" src="https://github.com/user-attachments/assets/226e3cbe-2033-4181-8c90-4058b8ef9c9d" />
