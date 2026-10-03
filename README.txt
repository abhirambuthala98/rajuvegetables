RAJU VEGETABLES refresh-session fix.

The owner login session and current section are kept in sessionStorage so a page refresh restores the same app section. Closing the browser/tab clears the session and requires login again. Business data remains in localStorage.
