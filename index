export default function CaseStudiesPage() {
  const cases = [
    {
      title: "Major Shipping Company",
      client: "Leading Shipping Company",
      challenge: "Key metrics unclear; operational data only accessible via lengthy Excel processes.",
      solution: "Built a unified KPI dashboard using SQL integrations and data transformations.",
      impact: [
        "Time to access critical figures cut from 3 days → 1 minute",
        "Clear performance visibility from C-suite to operations"
      ],
      image: "https://res.cloudinary.com/diopuimlo/image/upload/v1756293706/C1_h3qxcd.jpg"
    },
    {
      title: "Large Parcel Delivery Project",
      client: "Parcel Delivery Division",
      challenge: "Service losing EGP 200K/month, blocking expansion.",
      solution: "Built cost database + courier performance analytics using BigQuery + Google Sheets with Looker Studio dashboards.",
      impact: [
        "EGP 200K monthly loss → EGP 100K profit in 4 months",
        "Sustainable and scalable operational model"
      ],
      image: "https://res.cloudinary.com/diopuimlo/image/upload/v1756293706/C2_ckbzwx.jpg"
    },
    {
      title: "Trading & Distribution Company",
      client: "Trading & Distribution Firm",
      challenge: "Inaccurate accounts and poor inventory records caused repeated losses.",
      solution: "Integrated sales, purchasing, expenses, and inventory movements into one real-time dashboard.",
      impact: [
        "No further losses",
        "Daily cash and stock monitoring improved"
      ],
      image: "https://res.cloudinary.com/diopuimlo/image/upload/v1756293706/C3_jrglyw.jpg"
    },
    {
      title: "Customer Service Performance Visibility",
      client: "Service Provider",
      challenge: "Customers reported slow issue resolution while the service team claimed normal response times.",
      solution: "Audited ticketing process, linked tickets to agents, and created dashboards comparing resolution speed and efficiency.",
      impact: [
        "Full performance visibility for management",
        "Clear accountability and faster responses"
      ],
      image: "https://res.cloudinary.com/diopuimlo/image/upload/v1756293706/C4_pavkyb.jpg"
    },
    {
      title: "Consulting & Training Firm (with Ministry of Communications)",
      client: "Consulting & Training Provider",
      challenge: "Management surprised by incomplete performance indicators tracked manually.",
      solution: "Connected and modified existing attendance sheets to generate real-time performance metrics automatically.",
      impact: [
        "Early detection of incomplete KPIs",
        "Projects delivered on time with less manual effort"
      ],
      image: "https://res.cloudinary.com/diopuimlo/image/upload/v1756293706/C5_hrj0qp.jpg"
    }
  ];

  return (
    <div className="min-h-screen bg-gray-50" style={{ backgroundImage: 'url(https://res.cloudinary.com/diopuimlo/image/upload/v1756293118/back_x4luua.jpg)', backgroundSize: 'cover', backgroundRepeat: 'no-repeat', backgroundAttachment: 'fixed', opacity: 0.85 }}>
      {/* Header with logo and title */}
      <header className="bg-white bg-opacity-80 shadow p-4 flex flex-col items-center relative">
        <img src="https://res.cloudinary.com/diopuimlo/image/upload/v1756293118/Logo_iwse7a.jpg" alt="Bayanata Logo" className="h-36 absolute right-4 top-4" />
        <h1 className="text-2xl font-bold">Bayanata Case Studies</h1>
      </header>

      {/* Case studies grid */}
      <section className="p-8 grid gap-6 md:grid-cols-2 lg:grid-cols-3">
        {cases.map((c, index) => (
          <div key={index} className="bg-white bg-opacity-90 rounded-2xl shadow p-4 flex flex-col">
            <a href={c.image} target="_blank" rel="noopener noreferrer">
              <img src={c.image} alt={c.title} className="rounded-xl mb-4 object-cover h-40 cursor-pointer" />
            </a>
            <h2 className="text-xl font-semibold mb-2">{c.title}</h2>
            <p className="text-gray-700 text-sm mb-1"><strong>Client:</strong> {c.client}</p>
            <p className="text-gray-700 text-sm mb-2"><strong>Challenge:</strong> {c.challenge}</p>
            <p className="text-gray-700 text-sm mb-2"><strong>What We Did:</strong> {c.solution}</p>
            <ul className="list-disc list-inside text-gray-700 text-sm mb-2">
              {c.impact.map((item, idx) => (
                <li key={idx}>{item}</li>
              ))}
            </ul>
          </div>
        ))}
      </section>

      {/* Tools section */}
      <section className="bg-white bg-opacity-90 p-8 mt-8">
        <h2 className="text-2xl font-bold mb-4">Tools & Technologies</h2>
        <p className="text-gray-700 mb-6">
          We leverage modern BI and data platforms to deliver real-time insights and scalable solutions:
        </p>
        <ul className="list-disc list-inside text-gray-700 mb-6">
          <li>Looker Studio for interactive dashboards and visual reporting</li>
          <li>BigQuery for high-performance analytics at scale</li>
          <li>Google Sheets for flexible data handling and integration</li>
          <li>SQL Server for structured data processing and KPI standardization</li>
          <li>Additional integrations: Google Analytics, ClickHouse Server, and other specialized databases</li>
        </ul>
        <div className="grid grid-cols-1 md:grid-cols-2 gap-4">
          <a href="https://res.cloudinary.com/diopuimlo/image/upload/v1756293707/T1_wcal7p.jpg" target="_blank" rel="noopener noreferrer">
            <img src="https://res.cloudinary.com/diopuimlo/image/upload/v1756293707/T1_wcal7p.jpg" alt="Tools screenshot 1" className="rounded-xl shadow cursor-pointer" />
          </a>
          <a href="https://res.cloudinary.com/diopuimlo/image/upload/v1756293707/T2_w53tfm.jpg" target="_blank" rel="noopener noreferrer">
            <img src="https://res.cloudinary.com/diopuimlo/image/upload/v1756293707/T2_w53tfm.jpg" alt="Tools screenshot 2" className="rounded-xl shadow cursor-pointer" />
          </a>
        </div>
      </section>
    </div>
  );
}
