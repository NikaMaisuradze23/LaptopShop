# LaptopShop

ეს არის რედბერის ბუტკემპის დავალება

### Landing

საწყის გვერდზე უნდა გვქონდეს ორი მომქმედების გაკეთების საშუალება:
- ჩანაწერის დამატება
- ჩანაწერების სიის ნახვა

### თანამშრომლის ინფორმაცია

ჩანაწერის დამატებაზე დაჭერით გადავდივართ ფორმის შევსების პირველ გვერდზე, სადაც უნდა შევიყვანოთ თანამშრომლის ინფორმაცია ვისაც აქვს გადაცემული Redberry-ის ლეპტოპი ან უნდა გადაეცეს.
ფორმა უნდა შედგებოდეს შემდეგი შესავსები ინფორმაციებისა და ვალიდაციებისაგან:

- სახელი -ტექსტური ველი
  - ვალიდაცია:
   - სავალდებულო 
   - მინიმუმ 2 სიმბლოლო
   - მხოლოდ ქართული სიმბოლოები
- გვარი - ტექსტური ველი
  - ვალიდაცია:
   - სავალდებულო 
   - მინიმუმ 2 სიმბლოლო
   - მხოლოდ ქართული სიმბოლოები
- თიმი - ამოსარჩევი ველი
  - ვალიდაცია:
   - სავალდებულო 
- პოზიცია - ამოსარჩევი ველი
  - ვალიდაცია:
   - სავალდებულო
- მეილი - ტექსტური ველი
  - ვალიდაცია:
   - სავალდებულო
   - უნდა მთავრდებოდეს @redberry.ge-თი
- ტელეფონის ნომერი - ტექსტური ველი
  - ვალიდაცია:
   - სავალდებულო
   - უნდა აკმაყოფილებდეს ქართული მობილურის ნომრის ფორმატს
   
უნდა შეგვეძლოს მომდევნო გვერდზე გადასვლა, სადაც უკვე შევავსებთ ლეპტოპის შესახებ ინფორმაციას. 

## ლეპტოპის ტექნიკური მახასიათებლები

- ლეპტოპის სახელი - ტექსტური ველი
  - ვალიდაცია:
   - სავალდებულო 
   - შესაძლებელია შეიცავდეს მხოლოდ ლათინურ სიმბოლოებს, რიცხვებსა და !@#$%^&*()_+=
- ლეპტოპის სურათი - ფაილის ასატვირთი ველი
  - ვალიდაცია:
   - სავალდებულო 
- ლეპტოპის ბრენდი - ამოსარჩევი ველი
  - ვალიდაცია:
   - სავალდებულო 
- ლეპტოპის CPU - ამოსარჩევი ველი
  - ვალიდაცია:
   - სავალდებულო
- CPU-ს ბირთვი - ტექსტური ველ
  - ვალიდაცია:
   - სავალდებულო
   - მხოლოდ რიცხვი
- CPU-ს ნაკადი - ტექსტური ველი
  - ვალიდაცია:
   - სავალდებულო
   - მხოლოდ რიცხვი
- ლეპტოპის RAM(გიგაბაიტებში - GB) - ტექსტური ველი
  - ვალიდაცია:
   - სავალდებულო
   - მხოლოდ რიცხვი
- მეხსერების ტიპი - რადიო ღილაკი
  - ვალიდაცია:
   - სავალდებულო
  - ამოსაღჩევი ოფშენები:
   - SSD
   - HDD
- მეორადია თუ ახალი? - რადიო ღილაკი
  - ვალიდაცია:
   - სავალდებულო
  - ამოსაღჩევი ოფშენები:
   - ახალი
   - მეორადი
- შეძენის თარიღი - თარიღის ველი
  - ვალიდაცია:
   - არასავალდებულო
- ლეპტოპის ფასი(Gel) - ტექსტური ველი
  - ვალიდაცია:
   - სავალდებულო
   - მხოლოდ რიცხვი


ფორმის შევსების შემდგომ უნდა შეგვეძლოს ამ ჩანაწერის დამახსოვრება. თუ ვალიდაციის წესესები არ კმაყოფილდება უნდა დავინახოთ შესაბამისი error მესიჯები.

თუ ვალიდაციის წესები დაკმაყოფილებულია უნდა დაემატოს ახალი ჩანაწერი და დავინახოთ Success შეტყობინება, საიდანაც უნდა შეგვეძლოს საწყის გვერდზე დაბრუნება.


### დამატებული ლეპტოპების სია

ამ გვერდზე მოხვედრა შეგვიძლია Landing გვერდიდან.
აქ უნდა დავინახოთ ჩანაწერების სრული სია. 

თითოეულ ჩანაწერს უნდა ჰქონდეს შემდეგი მახასიათებელი:

- ლეპტოპის სურათი
- ლეპტოპის სახელი
- თანამშრომლის სახელი და გვარი
- სრულად ნახვის ღილაკი

სრულად ნახვის ღილაკზე დაკლიკებით გადავალთ ჩანაწერის შიდა გვერდზე სადაც დავინახავთ ყველა შევსებულ ინფორმაციას.
### თანამშრომლის ლეპტოპის შიდა გვერდი

ამ გვერდზე უნდა გამოჩნდეს ყველა შევსებული ინფორმაცია თანამშრომელზე და ლეპტოპზე რაც ოფის მენეჯერმა შეავსო. 

## დამატებითი მოთხოვნები

1.აპლიკაცია გამართულად უნდა მუშაობდეს, ისე როგორც დოკუმენტაციაშია აღწერილი
2.დიზაინი შესრულებული უნდა იყო ორ რეზოლუციაზე:
    1.დესკტოპზე (1920x1080)
    2.მობაილზე (390x844 - IPhone 12 Pro)
3.დარეფრეშებისას ინფორმაცია არ უნდა აიკარგებოდეს!
4.აპლიკაციის დაწერისთვის შეგიძლიათ გამოიყენოთ როგორც უბრალოდ JavaScript, ასევე ნებისმიერი სასურველი ფრეიმვორკი (Vue,Svelte, React, Angular ...)
5.უნდა გვქონდეს დისციპლინა კოდში, გიტჰაბის კომიტებში და ა.შ.
6.ჩვენ უნდა გვქონდეს დასრულებული აპლიკაციის ნახვის საშუალება, მაგალითად github pages, netlify, heroku და ა.შ. მეშვეობით და ასევე გიტჰაბის public რეპოზიტორიის ლინკი
7.თუ ჩვენ არ გვექნება შესრულებული აპლიკაციის public link-ზე ნახვის საშუალება, ეს ფაქტი დიდ გავლენას იქონიებს მონაწილის შეფასებაზე
8.მიაქციეთ დიდი ყურადღება ზემოთ ჩამოთვლილ კრიტერიუმებს და დანარჩენი კარგობების დამატებაზე შემდეგ იდარდეთ. მაგ: ლამაზი ანიმაცია და ა.შ.

## რესურსები

  - [Figma](https://www.figma.com/file/jgPDZNbHF7ePScgcEyLXZi/PCfy?node-id=1%3A52) 
  - [Token Generation](https://pcfy.redberryinternship.ge/) 
  - [API Documentation](https://pcfy.redberryinternship.ge/swagger)

