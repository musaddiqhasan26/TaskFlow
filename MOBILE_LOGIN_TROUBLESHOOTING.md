# Mobile Login Troubleshooting Guide

## Common Issues and Solutions

### 1. Firebase Configuration Not Set Up
**Symptoms:** Login fails immediately with configuration error
**Solution:** 
- Copy `js/config-template.js` to `js/config.js`
- Replace placeholder values with actual Firebase config from Firebase Console
- Ensure Firebase Authentication is enabled with Google provider

### 2. Mobile Popup Blockers
**Symptoms:** Login works on desktop but fails on mobile
**Solution:** 
- The app now automatically uses redirect method on mobile devices
- If still having issues, try enabling popups for the site
- Clear browser cache and cookies

### 3. Network/Connectivity Issues
**Symptoms:** "Network request failed" error
**Solution:**
- Check internet connection
- Try switching between WiFi and mobile data
- Disable VPN if using one
- Try a different browser

### 4. Browser Compatibility
**Symptoms:** Login button doesn't respond or shows errors
**Solution:**
- Use a modern browser (Chrome, Safari, Firefox, Edge)
- Update your browser to the latest version
- Clear browser cache and data
- Disable browser extensions temporarily

### 5. Third-Party Cookies Disabled
**Symptoms:** Login popup opens but fails to complete
**Solution:**
- Enable third-party cookies in browser settings
- Add exceptions for google.com and your domain
- Try incognito/private browsing mode

## Mobile-Specific Fixes Applied

1. **Automatic Mobile Detection:** App detects mobile devices and uses redirect instead of popup
2. **Better Error Messages:** More specific error messages for different failure scenarios
3. **Loading States:** Visual feedback during login process
4. **Configuration Validation:** Checks if Firebase is properly configured
5. **Redirect Handling:** Proper handling of OAuth redirect flow on mobile

## Testing Steps

1. Open the app on mobile device
2. Click "Sign in with Google"
3. Should redirect to Google login page (not popup)
4. Complete login on Google's page
5. Should redirect back to app and log you in

## If Still Having Issues

1. Check browser console for error messages
2. Try different browsers (Chrome, Safari, Firefox)
3. Test on different devices/networks
4. Verify Firebase configuration is correct
5. Check Firebase Console for authentication logs

## Firebase Setup Checklist

- [ ] Firebase project created
- [ ] Authentication enabled
- [ ] Google provider configured
- [ ] Authorized domains added (your domain + localhost for testing)
- [ ] Config values copied to config.js
- [ ] Web app registered in Firebase project

## Contact Support

If none of these solutions work, please provide:
- Device type and browser version
- Error messages from browser console
- Screenshots of the issue
- Network connectivity details