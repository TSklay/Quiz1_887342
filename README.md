# Quiz1_887342

ทำข้อ1.1 และ1.3 เสร็จแล้วครับ

US_states = 
		{"Alabama" => "AL",
	"Alaska" => "AK",
	"Arizona" => "AZ",
	"Arkansas" => "AR",
	"California" => "CA",
	"Colorado" => "CO",
	"Connecticut" => "CT",
	"Delaware" => "DE",
	"District of Columbia" => "DC",
	"Florida" => "FL",
	"Georgia" => "GA",
	"Hawaii" => "HI",
	"Idaho" => "ID",
	"Illinois" => "IL",
	"Indiana" => "IN",
	"Iowa" => "IA",
	"Kansas" => "KS",
	"Kentucky" => "KY",
	"Louisiana" => "LA",
	"Maine" => "ME",
	"Maryland" => "MD",
	"Massachusetts" => "MA",
	"Michigan" => "MI",
	"Minnesota" => "MN",
	"Mississippi" => "MS",
	"Missouri" => "MO",
	"Montana" => "MT",
	"Nebraska" => "NE",
	"Nevada" => "NV",
	"New Hampshire" => "NH",
	"New Jersey" => "NJ",
	"New Mexico" => "NM",
	"New York" => "NY",
	"North Carolina" => "NC",
	"North Dakota" => "ND",
	"Ohio" => "OH",
	"Oklahoma" => "OK",
	"Oregon" => "OR",
	"Pennsylvania" => "PA",
	"Rhode Island" => "RI",
	"South Carolina" => "SC",
	"South Dakota" => "SD",
	"Tennessee" => "TN",
	"Texas" => "TX",
	"Utah" => "UT",
	"Vermont" => "VT",
	"Virginia" => "VA",
	"Washington" => "WA",
	"West Virginia" => "WV",
	"Wisconsin" => "WI",
	"Wyoming" => "WY"}

ข้อ1.1ตัวย่อลงท้าย T หรือ N

US_states.each { |x, y|
if y.byteslice(-1) === "T" || y.byteslice(-1) === "N"
puts "#{y}" 
end}

ข้อ 1.3 สรขึ้นต้นและลงท้ายสระ

US_states.each { |key, y|
if key.byteslice(0) === "A" || key.byteslice(0) === "E" || key.byteslice(0) === "I" || key.byteslice(0) === "O" || key.byteslice(0) === "U" || key.byteslice(-1) === "a" || key.byteslice(-1) === "e" || key.byteslice(-1) === "i" || key.byteslice(-1) === "o" || key.byteslice(-1) === "u"
    puts "#{key}" 
end}
