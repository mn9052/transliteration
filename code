#include "Convertor.h"
namespace FA_TO_EN
{

	std::string Convertor::ConvertToFinglish(const std::string &sourceText)
	{
		std::string temp = "";

		for (int counter = 0; counter < sourceText.length(); counter++)
		{
			switch (sourceText[counter])
			{
				case 'a':
					if (counter != 0 && sourceText[counter - 1] == 'a')
						temp = temp.substr(0, temp.length() - 1) + 'ا';
					else
						temp += "َ";
					break;
				case 'A':
					temp += "آ";
					break;
				case 'b':
					temp += "ب";
					break;
				case 'c':
					temp += "ث";
					break;
				case 'd':
					temp += "د";
					break;
				case 'e':
					if (counter != 0 && sourceText[counter - 1] == 'e')
						temp = temp.substr(0, temp.length() - 1) + 'ه';
					else
						temp += "ِ";
					break;
				case 'E':
					temp += "ع";
					break;
				case 'f':
					temp += "ف";
					break;
				case 'g':
					temp += 'گ';
					break;
				case 'h':
					if (counter != 0 && sourceText[counter - 1] == 'c')
						temp = temp.substr(0, temp.length() - 1) + 'چ';
					else if (counter != 0 && sourceText[counter - 1] == 'g')
						temp = temp.substr(0, temp.length() - 1) + 'ق';
					else if (counter != 0 && sourceText[counter - 1] == 'G')
						temp = temp.substr(0, temp.length() - 1) + 'غ';
					else if (counter != 0 && sourceText[counter - 1] == 'k')
						temp = temp.substr(0, temp.length() - 1) + 'خ';
					else if (counter != 0 && sourceText[counter - 1] == 'j')
						temp = temp.substr(0, temp.length() - 1) + 'ژ';
					else if (counter != 0 && sourceText[counter - 1] == 's')
						temp = temp.substr(0, temp.length() - 1) + 'ش';
					else
						temp += 'ه';
					break;
				case 'H':
					temp += 'ح';
					break;
				case 'i':
					if (counter != 0 && sourceText[counter - 1] == 'e')
						temp = temp.substr(0, temp.length() - 1) + 'ئ';
					else
						temp += 'ی';
					break;
				case 'I':
					temp += "ای";
					break;
				case 'j':
					temp += "ج";
					break;
				case 'k':
					temp += "ک";
					break;
				case 'l':
					temp += "ل";
					break;
				case 'm':
					temp += "م";
					break;
				case 'n':
					temp += "ن";
					break;
				case 'o':
					if (counter != 0 && sourceText[counter - 1] == 'o')
						temp = temp.substr(0, temp.length() - 1) + 'و';
					else
						temp += "ُ";
					break;
				case 'p':
					temp += "پ";
					break;
				case 'r':
					temp += "ر";
					break;
				case 's':
					temp += "س";
					break;
				case 'S':
					temp += "ص";
					break;
				case 't':
					temp += "ت";
					break;
				case 'T':
					temp += "ط";
					break;
				case 'u':
					temp += "و";
					break;
				case 'v':
					temp += "و";
					break;
				case 'w':
					temp += "";
					break;
				case 'x':
					temp += "س";
					break;
				case 'y':
					temp += "ی";
					break;
				case 'z':
					temp += "ز";
					break;
				case 'Z':
					temp += "ذ";
					break;
				default:
					temp += sourceText[counter];
					break;
			}
		}

		return temp;
	}
}
