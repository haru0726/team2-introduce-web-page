# team2-introduce-web-page
팀 소개 웹페이지용 깃허브 레포지토리

# 파이어베이스 SDK
// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyCdU8NhpFT6489DMGs2MPWQSdJR5QbRJoI",
  authDomain: "team2-introduce-web-page.firebaseapp.com",
  projectId: "team2-introduce-web-page",
  storageBucket: "team2-introduce-web-page.appspot.com",
  messagingSenderId: "970550082038",
  appId: "1:970550082038:web:a526f70bcd79eece032fd7",
  measurementId: "G-XHELKFT8ZL"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);
