# kajol-portfolio
import React from "react";
import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";

export default function Portfolio() {
  return (
    <main className="p-6 max-w-4xl mx-auto space-y-10">
      {/* Hero Section */}
      <section className="text-center space-y-2">
        <h1 className="text-4xl font-bold">Howdy! I'm Kajol Kumari</h1>
        <p className="text-lg text-gray-600">
          Health Informatics Graduate Student @ Northeastern University | Graduating Dec 2025
        </p>
        <p className="text-md text-gray-500">kumari.ka@northeastern.edu</p>
        <a
          href="https://www.linkedin.com/in/kajol-kumari-b808111a5/"
          target="_blank"
          className="text-blue-600 hover:underline"
        >
          LinkedIn Profile
        </a>
      </section>

      {/* About Me Section */}
      <Card>
        <CardContent className="space-y-4">
          <h2 className="text-2xl font-semibold">About Me</h2>
          <p>
            I’m a Health Informatics grad student passionate about healthcare analytics, AI, and Electronic Health Records. I'm currently seeking Summer 2025 internships and full-time roles where I can contribute to data-driven healthcare solutions.
          </p>
          <p>
            With a Bachelor’s in Dental Surgery, I’ve worked as a Dental Assistant and Intern, gaining hands-on experience with Open Dental software, analyzing patient data, and contributing to clinical research.
          </p>
          <p>
            When I’m not deep into data or healthcare systems, I’m likely sleeping, binge-watching my favorite shows, or checking off bucket list adventures!
          </p>
        </CardContent>
      </Card>

      {/* Skills Section */}
      <Card>
        <CardContent>
          <h2 className="text-2xl font-semibold mb-2">Skills & Tools</h2>
          <ul className="list-disc pl-5 space-y-1">
            <li>SQL, R, MySQL, R Markdown</li>
            <li>Tableau, Power BI</li>
            <li>Open Dental, Electronic Health Records (EHR)</li>
            <li>Healthcare Data Management & Analytics</li>
            <li>Microsoft Office Suite</li>
            <li>Communication, Project Management, Critical Thinking</li>
          </ul>
        </CardContent>
      </Card>

      {/* Projects Section */}
      <Card>
        <CardContent className="space-y-3">
          <h2 className="text-2xl font-semibold">Projects</h2>
          <div>
            <h3 className="text-lg font-medium">Panion App – EthiCare Innovators</h3>
            <p>
              Led market research for a Canadian healthcare app, identifying key players, regulations, and launch strategy. Collaborated with teams on risk mitigation and technical documentation.
            </p>
          </div>
        </CardContent>
      </Card>

      {/* Research Section */}
      <Card>
        <CardContent className="space-y-3">
          <h2 className="text-2xl font-semibold">Publications</h2>

          <div>
            <h3 className="font-medium">
              <a
                href="https://www.cureus.com/articles/190462-unraveling-the-complexity-of-apert-syndrome-genetics-clinical-insights-and-future-frontiers#!/"
                className="text-blue-600 hover:underline"
                target="_blank"
              >
                Unraveling the Complexity of Apert Syndrome
              </a>
            </h3>
            <p className="text-sm text-gray-600">
              Published in Cureus Journal of Medical Science (2023)
            </p>
            <p>
              Explored genetic mechanisms and clinical aspects of Apert Syndrome while highlighting future directions in treatment, including gene-editing and multidisciplinary care.
            </p>
          </div>

          <div>
            <h3 className="font-medium">
              Knowledge and Awareness About Occupational Hazards Among Dentists
            </h3>
            <p className="text-sm text-gray-600">
              Published in Med Forum, Volume 34, Issue 5 (May 2023)
            </p>
            <p>
              Surveyed 300 dentists in Karachi to assess awareness of risks such as needle-stick injuries, radiation, and stress. Contributed to data analysis and interpretation.
            </p>
          </div>
        </CardContent>
      </Card>

      {/* Contact Section */}
      <Card>
        <CardContent className="space-y-2">
          <h2 className="text-2xl font-semibold">Contact Me</h2>
          <p>Email: <a href="mailto:kumari.ka@northeastern.edu" className="text-blue-600">kumari.ka@northeastern.edu</a></p>
          <Button asChild>
            <a href="/Kajol_Kumari_Resume.pdf" download>
              Download Resume
            </a>
          </Button>
        </CardContent>
      </Card>
    </main>
  );
}
