# registration-form-v1
I build this project to be reusable in other projects later on. I build the requirements and the design based on quick research on several companies's training program registration form. The research document will not be shared here, but I can share the result.

# Fields Required in the Registration Form
0. Field (format/regular expression)
## Obligatiory
1. Full Name (Alphabet)
2. Valid Email (Alphanumeric, symbols, [@], domain)
3. Correspondence Address (Alphanumeric, symbols)
4. Mobile Number (Country Code (begin with +), numeric)
## Optional
1. Gender (Male/Female)
2. Company/Institution (Alphanumeric, symbols)
3. Birth Date (Date)
4. Telephone/Fax Number (Country Code (begin with +), numeric)
5. Training Type (Multiple selection from available type)
6. Training Schedule (Date)
7. Payment Proof (Image)
8. Person In Charge (PIC) of Payment Name (Alphabet)
9. PIC of Payment Phone Number (Country Code (begin with +), numeric)
10. PIC of Payment Email (Alphanumeric, symbols, [@], domain)
11. PIC of Payment Address (Alphanumeric, symbols)
12. Additional Notes (Alphanumeric, symbols)
## My Additional Fields
1. Occupation (Alphanumeric, symbols)
2. Field of Expertise (Choose from available field of expertise)
3. Whatsapp Mobile Number (Country Code (begin with +), numeric)
4. Domicile (Choose from available city)

# General Components
All fields mentioned at the previous section can be grouped into general components based on its format. Below are the general components that should be built. I also present the suggested shape for each component.
1. Alphabetic Input (long text box, short text box)
2. Email Input (short text box)
3. Alphanumeric & Symbols Input (long text box, short text box)
4. Phone Number Input (short text box)
5. A/B Selection (radio button)
6. Date Input (date picker)
7. Image Input (browse file)
8. Multiple Selection Input (checkboxes)
9. Unique Selection (dropdown list, radio button)
