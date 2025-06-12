import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { Mail, Phone, MapPin, Linkedin, Download } from "lucide-react";

export default function CurriculumRoy() {
  return (
    <div className="p-6 max-w-4xl mx-auto grid gap-6">
      <Card className="text-center">
        <CardContent className="p-6">
          <h1 className="text-3xl font-bold">Roi Bacelo</h1>
          <p className="text-lg text-gray-600">International Seafood Sales Representative</p>
        </CardContent>
      </Card>

      <Card>
        <CardContent className="p-6">
          <h2 className="text-xl font-semibold mb-2">Contact</h2>
          <div className="grid gap-2">
            <div className="flex items-center gap-2"><Phone size={16}/> +34 664 51 68 56</div>
            <div className="flex items-center gap-2"><Mail size={16}/> roibacelo@eueevigo.es</div>
            <div className="flex items-center gap-2"><MapPin size={16}/> Vigo (Pontevedra)</div>
            <div className="flex items-center gap-2"><Linkedin size={16}/> <a href="#" className="text-blue-600">LinkedIn</a></div>
            <div className="flex items-center gap-2"><Download size={16}/> <a href="/RoiBaceloCV.pdf" download className="text-blue-600">Download PDF</a></div>
          </div>
        </CardContent>
      </Card>

      <Card>
        <CardContent className="p-6">
          <h2 className="text-xl font-semibold mb-2">Professional Summary</h2>
          <p>
            Sales professional with experience in the fresh and refrigerated seafood industry. C1 level English and academic background in international trade. Looking to grow within export-focused companies in the seafood sector.
          </p>
        </CardContent>
      </Card>

      <Card>
        <CardContent className="p-6">
          <h2 className="text-xl font-semibold mb-2">Work Experience</h2>
          <ul className="list-disc list-inside space-y-2">
            <li>
              <strong>Sales Representative at Velomar Pesca S.L.</strong> (Nov 2023 – Jun 2025)
              <ul className="list-disc ml-5">
                <li>Direct management of international seafood clients</li>
                <li>Contact with importers and distributors</li>
                <li>Preparation and follow-up of customized commercial offers</li>
                <li>Knowledge of commercial species (whitefish, bluefish, cephalopods)</li>
                <li>Experience with Spanish, Portuguese and French fish markets</li>
              </ul>
            </li>
            <li>
              <strong>Consultant at DPI Estrategia</strong> (Oct 2022 – Dec 2022)
              <ul className="list-disc ml-5">
                <li>Time management and report writing</li>
                <li>Teamwork and data analysis</li>
              </ul>
            </li>
          </ul>
        </CardContent>
      </Card>

      <Card>
        <CardContent className="p-6">
          <h2 className="text-xl font-semibold mb-2">Education</h2>
          <ul className="list-disc list-inside space-y-2">
            <li><strong>Master’s in International Business and Foreign Trade</strong> – IFFE Business School (2023 – 2024)</li>
            <li><strong>Bachelor’s Degree in Commerce</strong> – University of Vigo (2019 – 2023)</li>
          </ul>
        </CardContent>
      </Card>

      <Card>
        <CardContent className="p-6">
          <h2 className="text-xl font-semibold mb-2">Skills</h2>
          <ul className="list-disc list-inside">
            <li>English – C1 level</li>
            <li>Basic French with professional focus</li>
            <li>Microsoft 365 proficiency</li>
            <li>Knowledge of cold chain logistics</li>
            <li>Own vehicle and immediate availability</li>
          </ul>
        </CardContent>
      </Card>
    </div>
  );
}
