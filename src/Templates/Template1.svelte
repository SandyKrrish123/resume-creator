<script>
    export let resume = {
        WantedJobTitle: { value: "Engineer", type: "text" },
        FirstName: { value: "Santhosh", type: "text" },
        Description: {
            value: "Santhosh@example.com",
            type: "textarea",
            class: "full-width",
        },
        Email: { value: "Santhosh@example.com", type: "email" },
        Country: { value: "India", type: "text" },
        LastName: { value: "Kumar", type: "text" },
        Phone: { value: "1234567890", type: "tel" },
        City: { value: "Chennai", type: "text" },
        Address: { value: "Chennai", type: "text" },
        PostalCode: { value: "600100", type: "text" },
        Nationality: { value: "Indian", type: "text" },
        DateOfBirth: { value: "1996-09-10", type: "date" },
    };
</script>

<div class="container">
    <header>
        <h1>{resume.FirstName.value} {resume.LastName.value}</h1>
        -->
        <p>Your Profession</p>
        <div class="contact-info">
            <p><strong>Email:</strong> {resume.Email.value}</p>
            <p><strong>Phone:</strong> {resume.Phone.value}</p>

            <p>
                <strong>Address:</strong> 123 Main Street, {resume.City.value} ,
                State,{resume.PostalCode.value}
            </p>
        </div>
    </header>
    <main>
        <section>
            <h2>Summary</h2>
            <p>A brief summary about yourself and your professional goals.</p>
        </section>
        <section>
            <h2>Experience</h2>
            <div class="experience">
                <h3>Job Title</h3>
                <p>Company Name, Location</p>
                <p>Start Date - End Date</p>
                <ul>
                    <li>Job responsibility 1</li>
                    <li>Job responsibility 2</li>
                    <li>Job responsibility 3</li>
                </ul>
            </div>
            <!-- Add more experience sections as needed -->
        </section>
        <section>
            <h2>Education</h2>
            <div class="education">
                <h3>Degree or Certification</h3>
                <p>Institution Name, Location</p>
                <p>Graduation Year</p>
            </div>
            <!-- Add more education sections as needed -->
        </section>
        <section>
            <h2>Skills</h2>
            <ul>
                <li>Skill 1</li>
                <li>Skill 2</li>
                <li>Skill 3</li>
            </ul>
        </section>
    </main>
</div>

<style>
    /* Reset some default styles */
    body,
    h1,
    h2,
    h3,
    p,
    ul {
        margin: 0;
        padding: 0;
    }

    body {
        font-family: Arial, sans-serif;
        line-height: 1.5;
    }

    .container {
        max-width: 800px;
        margin: 0 auto;
        padding: 20px;
    }

    header {
        text-align: center;
        margin-bottom: 30px;
    }

    h1 {
        font-size: 36px;
        margin-bottom: 10px;
    }

    .contact-info {
        margin-top: 10px;
    }

    main {
        margin-bottom: 30px;
    }

    section {
        margin-bottom: 20px;
    }

    h2 {
        font-size: 24px;
        margin-bottom: 10px;
    }

    h3 {
        font-size: 18px;
        margin-bottom: 5px;
    }

    ul {
        list-style-type: disc;
        margin-left: 20px;
    }

    .experience,
    .education {
        margin-bottom: 15px;
    }
</style>
