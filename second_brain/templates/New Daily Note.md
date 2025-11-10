<%*
// 1. Define the filename: YYYY-MM-DD
const filename = tp.date.now("YYYY-MM-DD");

// 2. Find the TFile object for your main template
const template = tp.file.find_tfile("templates/daily"); 
// IMPORTANT: The name inside find_tfile() must match your template file name exactly (e.g., "Daily")

// 3. Define the folder where the new file should be created
const folder = "notes/journal/daily/"; // <-- **CHANGE THIS to your desired folder!**

// 4. Create the new file using the template content and the dynamic filename
await tp.file.create_new(template, filename, true, folder);
// Arguments: (template object, filename string, open_new: true/false, folder string)
-%>