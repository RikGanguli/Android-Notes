<h1>Personal Notes App</h1>

<p>This Android app allows users to create and manage personal notes. Each note consists of a title, note content, and a last-update timestamp. The app stores and retrieves notes in JSON format from the internal file system. It is built using <strong>Android Studio</strong> and <strong>Java</strong>.</p>

<h2>Features</h2>
<ul>
  <li>Create and manage an unlimited number of personal notes.</li>
  <li>Each note includes:
    <ul>
      <li><strong>Title</strong></li>
      <li><strong>Note text</strong></li>
      <li><strong>Last update time</strong></li>
    </ul>
  </li>
  <li>Notes are saved in JSON format in the internal file system.</li>
  <li>Notes are loaded on app startup from the JSON file if available, otherwise, the app starts with no existing notes.</li>
  <li>Notes can be added, updated, and deleted, with changes saved to the file system automatically.</li>
  <li>Supports both portrait and landscape orientations without needing different layouts.</li>
</ul>

<h2>Technologies Used</h2>
<ul>
  <li><strong>Android Studio</strong> - Development environment.</li>
  <li><strong>Java</strong> - Programming language.</li>
  <li><strong>RecyclerView</strong> - For displaying a list of notes.</li>
  <li><strong>Multiple Activities</strong> - For navigating between different screens.</li>
  <li><strong>JSON File</strong> - For saving and loading notes.</li>
  <li><strong>Option Menus</strong> - For menu-based interactions.</li>
</ul>

<h2>Setup and Installation</h2>
<ol>
  <li>Clone the repository:
    <pre><code>git clone https://github.com/RikGanguli/Android-Notes.git</code></pre>
  </li>
  <li>Open the project in Android Studio.</li>
  <li>Ensure you have the required dependencies in your <code>build.gradle</code> file (e.g., RecyclerView, etc.).</li>
  <li>Run the app on an Android device or emulator.</li>
</ol>

<h2>Usage</h2>
<ul>
  <li>On launch, the app loads any existing notes from the internal JSON file.</li>
  <li>If no notes are available, the app starts with an empty screen.</li>
  <li>Create a new note by tapping the add button and entering a title and note text.</li>
  <li>Delete or update notes, and the changes will be saved automatically to the JSON file.</li>
  <li>Notes are displayed in a list using RecyclerView, and each note shows its last update time.</li>
</ul>

<h2>Screenshots</h2>
<p></p>

<h2>Credits</h2>
<p>Developed by Rik Ganguli Biswas</p>
