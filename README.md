# Todo-App
Creating a Todo App with delete , localstorage add functionality. | Tech / Html, css, javaScript

```
import Image from 'next/image';

const ProfileHeader = () => {
  return (
    <div className="w-full bg-gray-900 text-white p-4 md:p-8">
      <div className="max-w-6xl mx-auto flex flex-col md:flex-row items-center md:items-start">
        {/* Profile Image */}
        <div className="flex-shrink-0">
          <Image
            src="/profile-pic.jpg" // Replace with your image path
            alt="Profile Picture"
            width={120}
            height={120}
            className="rounded-full border-4 border-white"
          />
        </div>
        {/* User Info */}
        <div className="md:ml-6 mt-4 md:mt-0 flex-1">
          <h1 className="text-3xl font-bold">Max Anderson</h1>
          <p className="text-lg">179 Supporters</p>
        </div>
        {/* Action Buttons */}
        <div className="mt-4 md:mt-0 md:ml-auto flex space-x-2">
          <button className="bg-yellow-500 text-black py-2 px-4 rounded">Donate</button>
          <button className="bg-white text-black py-2 px-4 rounded">Follow</button>
          <button className="bg-gray-800 text-white py-2 px-4 rounded">Message</button>
        </div>
      </div>
    </div>
  );
};

export default ProfileHeader;

```